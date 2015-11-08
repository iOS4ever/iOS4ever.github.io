---
layout: post
title: Week 11 – Trade with the dead
---
Hello, tomb raiders.

It was another solid and enriching week of class in OOP. Let me just jump straight into what we learned.

```
	T&& var
```

That, if I remember it correctly, is called an r-value reference. We have been using constant references to prevent copying objects to save time and space, but there’s still a problem: what if we are being passed in an r-value and we do want to keep whatever the temporary object holds? Well, we copy them obviously, right? Of course, Downing being Downing, he gave us another brilliant analogy. I really don’t want to spoil the entire thing for the future OOP students, but man it’s too good to not share it here. Don’t worry, you will still appreciate the analogy when you hear Downing says it himself. It is just not the same without hearing it in person. And yes, I modified a little bit just so it’s less, um, Downingy.

Imagine that you are in Ancient Egypt and a rich man died. The guy is going to be buried with his gold and jewelry the very next morning. You, being a poor worker, has a bunch of useless stuffs lying around. You know that those goodies are not going to see the daylight again once it is underground and you want those stuffs. What do you do now? It’s time to swap your junks with the dead man’s goods!

So, if a constructor was passed a temporary, doing a copy is just unnecessary because we know the temporary will soon to be destroyed; therefore, why not just use the useful space that was already allocated for the r-value? In short, instead of copying everything, we should just swap the pointers! We also learned that move( ) is actually a cast, but whatever.

By the way, Professor Downing did not show up for his office hour on Friday. My friends and I have been trying to go to Downing’s office after the lecture on Friday just to chat with him. Why? Because why not. Why so? Because we want to. It was our third attempt and this time we did not even get to see him. The first time he was chatting with someone else and the second time he was actually helping the students. Let’s hope that we can at least have one conversation before Thanksgiving. Professor, if you are reading this, you are not getting away! We will find you…

**Tip of the Week**: 

Do you shop on Amazon.com? If you do, you may want to check out Amazon Smile. If you make a purchase that is eligible for Amazon Smile, AmazonSmile Foundation will donate 0.5% of what you spent to the nonprofit organization of your choice. If you don’t know what organization to support, here are my top three: Animal Wonders Inc, Austin Pets Alive, and, since we’re CS majors, Code.org. Note that you’ll have to shop on smile.amazon.com, so don’t forget to bookmark it! Happy Black Friday shopping everyone!
