<link rel="canonical" href="https://levelup.gitconnected.com/flagged-enumerations-how-to-represent-features-combinations-into-one-field-f32e46a0885?sk=38b7a167ac8bbcf3bbd876155c68039c" />

# Flagged Enumerations: How To Represent Features Combinations Into One Field
### Represent features like [Read, Write, Modify, …] and their combinations into a single field.

<p align="center">
  <img src="https://miro.medium.com/max/1400/1*RLZE9dwBXcnZGTZ_-ZexlQ.jpeg">
</p>

<br/>

<p>
Sometimes when building your Software system and while designing a set of modules, you find that every module of these modules could -or couldn’t- support some features of a predefined list of features. At the end, there should be some field or property which maps each module to its supported features.
</p>

<br/>

<p>
For example, let’s say that we are working on a game where every character in the game would -or wouldn’t- be able to:<br/>
▶ Walk<br/>
▶ Run<br/>
▶ Speak<br/>
▶ Scream<br/>
▶ Fight<br/>
▶ …
</p>

<br/>

<p>
A character might support the features Walk, Run, and Speak only. Another character might support the features Walk, Scream, and Fight only. And so on,…
</p>

<br/>

<p>
Now, let’s say that you want to have only one field or property on the Character class to represent these features so that at any time using the value of this property you can know all the singular features supported by a certain Character instance.
</p>

<br/>

<p>
How would you do this? Someone might say: Use Flagged Enumerations, it is easy.
</p>

<br/>

<p>
Yes, this is right, but, do you know the concept that is already used in Flagged Enumerations? This is what this article is about.
</p>

<br/>

If you are interested into reading more about this topic, you can read [the rest of the article][Article]. 

<br/>

## If you want to support me:
▶ Subscribe to Medium using [my referral link][Membership]<br/>
▶ Subscribe to [Medium Newsletter][Subscribe]<br/>
▶ Subscribe to [LinkedIn Newsletter][Newsletter]<br/>
▶ Follow me on [Medium][Blog]<br/>
▶ Follow me on [Twitter][Twitter]<br/>
▶ Follow me on [LinkedIn][LinkedIn]

<br/>

## Authors:
* [Ahmed Tarek Hasan]


[Ahmed Tarek Hasan]: https://medium.com/@eng_ahmed.tarek
[Blog]: https://medium.com/@eng_ahmed.tarek
[Membership]: https://medium.com/@eng_ahmed.tarek/membership
[Subscribe]: https://medium.com/subscribe/@eng_ahmed.tarek
[Twitter]: https://twitter.com/AhmedTarekHasa1
[LinkedIn]: https://www.linkedin.com/in/atarekhasan/
[Friend Links]: https://www.linkedin.com/feed/update/urn:li:activity:6866082670108143616/
[Newsletter]: https://www.linkedin.com/newsletters/development-simply-put-6866647119655247872/
[Article]: https://levelup.gitconnected.com/flagged-enumerations-how-to-represent-features-combinations-into-one-field-f32e46a0885?sk=38b7a167ac8bbcf3bbd876155c68039c
