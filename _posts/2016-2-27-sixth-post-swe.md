---
layout: post
title: Week 6 – Bug vs. Feature
---
Hello, white squirrel.


Yes, I’m current staring at a man feeding the famous white squirrel behind GDC while many people have their phones out taking pictures. That little guy sure is adorable. Now it’s begging for more food from another man who is busy studying. I really don’t think he is gonna… oh hey, he gave it a piece of… um… bread?


Oh wait, this is not supposed to be a wildlife journal. My apologies.


Let me bring the subject back to the beautiful CS world of software engineering. 


We went over function defaults and unwrapping in Python this week. I think most of us are very familiar with function defaults, but what exactly is unwrapping? Personally, I think it is very similar to dereferencing. Here is a snippet of the code:

```
t = (1, 2)
def f (x = 10, y = 20):
	return [x, y]
print(f(t))	// [(1, 2), 20]
print(f(*t))  // [1, 2]
```

Hopefully you now see why I think it’s a bit like dereferencing in C. t is a tuple, but that is really just a disguise. It is actually just an address of where *1* is stored. If you put * in front of t, you’d be able to get the content within the tuple instead of the tuple itself.


That brings me to the weirdest part of this week’s adventure in Python – mutable function defaults. Consider the following code:

```
def g(arg = []):
	arg += [117]
	return arg

print(g())	// *a*
print(g())	// *b*
```

Pretty much everyone can agree that [117] would be printed out at *a*, but what I did not expect was what Python does at *b*. It turns out that the size of list that's returned at b is 2. In other words, this function keeps track of this mutable list.

I immediately asked Downing if this was a feature or a bug. Downing just told us that it is a “philosophical question.” He also added that it's not a bug in a sense that they have no plan to change it.


Personally, I think it was a bug and they were just too lazy to fix it and called it a feature instead. Just my 2 cents. 


We also got our second guest speaker of the semester this Wednesday! I already wrote too much for this week’s entry though, so I’m not going to talk about it.



**What did you do this past week?**


I started studying some Python in preparation for the upcoming storm.


**What’s in your way?**


There should be a function default for this. If I don’t put in anything here, it’d automatically put quizzes in here. Anyway, the evil exam 1 is in my way, and its job is to torture innocent people such as myself.


**What will you do next week?**


More studying just so I can survive the exam.


**Tip of the Week**: 


Tony Fadell, the father of iPod, gave a TED talk last year about attention to details when it comes to design. He made a great deal about how we humans habituate minor annoyances in our lives instead of trying to improve upon them. Although we are programmers, everyone of us has been on the other end of the spectrum – users. We notice good designs when we see them and bash on applications when we see poor designs. It’s very important for us to understand how we can be more considerate when it comes to problem solving with our skills and how to improve what we already have.

Enough of me talking (writing), here’s the [link]( http://www.ted.com/talks/tony_fadell_the_first_secret_of_design_is_noticing) to the talk.

By the way, the sticker on your fruit is actually edible, so you can totally ignore it if you’re really that impatient :)
