---
layout: post
title: Week 4 – Just a Reference
---

Hello hackers.

This week was really interesting for me because two of the articles we had to read involve space exploration, and boy I love space. Why are we reading stuffs about space? Well, it’s not about space exploration per se, but really about catching bugs. You may think that agencies like NASA and ESA would have countless of rigorous reviews of their software before they launch their billions of dollars rockets, and if there is a bug on their programs, it would be either very minor or something so complicated that only the software engineers working on the project would understand. That, however, is not the case. In short, NASA had a bug that was caused by missing a hyphen and ESA had a bug because they were attempting to fit a 64-but number into a 16-bit one. How on **Earth** did that even happen? Technically, it happened in space.

Anyway, what Prof. Downing taught us this week about coding is that our programs will always have bugs. The question is, what can we do to make the errors stand out so it’s much easier for the programmers to catch them? We talked about how we can make sure that certain functions would cause compile errors instead of runtime errors when something weird is being passed to the function and how that is useful. Runtime errors depend on execution path; therefore, it’s much harder to be caught. Downing also showed us some useful examples. When a function expects a reference but is being passed a NULL, an error will pop up right away when the program is being compiled. However, if a function expects a pointer but is being passed a NULL, the compiler wouldn’t know, and only when you need that function to do something awesome, you then realize that there is a bug. On the bright side, I guess most of us don’t have to beam our patch across the solar system to fix our program.

**Tip of the Week**: 

If you are new to C++ like me, this [C++](http://www.cplusplus.com) website is a very useful reference. It sure helps me code in C++ more effectively.

**Tip of the Week 2**

Monday is C(N)S Career Fair. If you have an iPhone or an Android, good news! You can download the official app and start planning your trip to your future company! Click [here]( http://email.mail.joinhandshake.com/c/eJw9T0FuxCAQe024LYIwIZMDh0rVfqAPiAjMFrYEokCk9vdle6hk-WDZlu0NotuQRTMKOYlFaqkFiImPIGDhiAphALHbmPizxBxs9jXYL-Ku7Cz01EPMDmB7CGm9nHEiUFpum0XhNGqWTGjtqIN6G8Z7R2xXpsrtcaS_ji5dtVMXOjdyIZdUPn9u1UXKjm7OnkTnK-mlUPOkYUE9qPveBvWO7DRPXmNL3QLCXrXFzK9G37Zy8hdrRsPtw4VSEvvfvu621pVep9bozaQX_QuY81L5) for iOS and [here]( http://email.mail.joinhandshake.com/c/eJw9j9FqxSAMhp-m3k1iqx698OLA6AvsAYo12dEzW0u1sL393GCDwB_Cl_x_0BkTVsOSG0EosEILDRIUHyVIy42ZjBwkbD5l_ixpj37HGv0H8VA2Ft3NA4CeREBLKEmjWjEoZe0qem9vLLvY2lGH6T6Mc68j-y_-KOWRf0_0SW3lpK7-6Ng4I7Vu1hfmhMP0Snjxq9Gnrzzs9V0odronr6llOnswf9WW9j-iw6w5LV_eQiwls_-0y-ZrXejnjSWhU9rqb8XXUAE) for Android.

**Tip of the Week 3** (man. I’ve got a lot of stuffs to share this week.)

If you are interested in space and our future trip to Mars **and** happened to be a CS major, you may want to check out this [article]( http://research.microsoft.com/en-us/um/people/mbj/Mars_Pathfinder/Mars_Pathfinder.html) about Mars rover Pathfinder.
