---
layout: post
title: Week 9 – Friends (with Benefits)
---
Hello, friends.

This week was quite interesting. First of all, I would like to brag about my achievement from the Friday lecture. I successfully predicted that Downing would call on me just five seconds before he said my name. The bad news is that I probably just wasted my future-predicting ability on this class instead of on the lottery. Oh well.

Let me go back to Monday. We went over vectors, but I’m not going to talk about it because I don’t remember any of it (yes, I’m kidding). On Wednesday, we delved further into vectors and talked about the difference between using the constructor for the array and the allocator and why it’s more efficient to use the allocator. Want to know why? You may want to take this class. We also went over three different containers, stack, queue, and priority queue, and what data structures support their implementations.

Friday lecture, once again, was the best one of the week. It can be divided into two parts – implicit type conversion and friends. The first part was especially interesting for me because I encountered it while I was studying for the midterm. I built a bidirectional iterator and put the following code to test them just out of curiosity, and yes, I expected it to fail.

```
  Bi_Iterator<int> bi1 = 3;     
  *bi1 = 2;     
  assert(bi1 == 2);    
```
To my surprise, it passed, and my mind was blown. After a long investigation, i.e., putting cout in a bunch of places, it turned out that it was calling the constructor for the 2. I made a conclusion that the compiler automatically casts it to an iterator so it can make the comparison. It turns out that I was kind of right. It is actually called “implicit type conversion,” and boy is it fun. We were then introduced to the explicit keyword. It basically tells the compiler to not make any assumption, and if a function/method call does not behave the way it is expecting, it would not compile. So, if my bidirectional iterator constructor had *explicit* in front of it, the assertion should fail. I haven’t tried it yet, but I trust Downing.

We then talked about friendship. It is a way for non-member function to access information that’s declared private. My partner and I used it to test our private functions in project 3, but I was not sure how it actually worked. This led us to the C++ joke that Downing mentioned at the end of the class. I made some modification inside the parentheses to make it less creepy:

*A friend (with benefits, hopefully) has all the access to your private parts.*



**Tip of the Week: Halo Edition**

Halo 5 is coming out this Tuesday! If you have read my previous blog posts or just know me in person, you know that I’m a complete Halo nerd, a.k.a. a Spartan. The developer of the series, 343 Industries, posted a behind the scene series called “The Sprint.” A sprint is usually a two-week deadline, and it is not unique to 343 Industries. If you are interested, I strongly recommend you to go to YouTube and checkout the videos. 

I also want to post the first episode of the third season as it gives a peak into the music composing process. One of the best things of Halo is that it has one of the best soundtracks in the world, and as a music lover, it is one of the major reasons why I’m so attached to the series (being a space junkie also helped :) ). 

Here is the [video]( https://www.youtube.com/watch?v=sQDkJwenbUE). If you just want to hear the music part, you can keep over to [10:55](http://www.youtube.com/watch?v=sQDkJwenbUE&t=11m55s) mark. I will be lying if I say my eyes did not get watery when I first heard this. It is a love letter to us Halo fans.

Anyway, I sure hope that some of you can also enjoy this piece of art. I also just realized that this has become a long post. Oops!

