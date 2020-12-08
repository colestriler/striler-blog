---
title: To figure out what is, first figure out what is not
date: "2020-12-08T22:12:03.284Z"
description: "Blog introduction, my goals, what to expect, and more."
---

You’re driving down the road and your car begins making a strange noise. So you pop open the hood and take a look at the hundreds of possibilities it could be. What do you do?

You start by figuring out what the problem is not. The two broadest categories most car problems fit under are gas and electric. Eliminate one and proceed down the other. Say the problem only occurs when you accelerate the throttle, so eliminate electric and start with gas. 

When you go to a doctor because of a pain, the first thing they will ask you is “where does it hurt?” They are trying to pinpoint the pain. You say “right here on my arm” and immediately, you eliminate hundreds of possibilities that it’s not. Now, the doctor can begin brainstorming possibilities within the correct region. Hopefully it’s not gas. (Joke)

I was once building a website which had two main components: a server and a database. I knew there was a bug in my code, but I didn’t know which component it was in. I tested every piece of the database and everything was working fine. Then, I went to the server and ran all the same tests. The server was fine too. If it wasn’t the database and it wasn’t the server, the ONLY thing it could have been was my own computer. So I restarted my computer, and the bug went away.

To solve hard problems, first identify categories that make up the system you’re working on. Use intuition or context clues to choose one to explore first. If it’s a car, first identify: gas or electric? If it’s medical, first identify which part of the body. Then, is it bone, muscular, or joints? If it’s code, think about what the code is doing, where it’s weaknesses are, and most importantly, set breakpoints.

## Always run in debug mode

To those who don’t know code, setting breakpoints allow you to stop a running command midway through its execution and visualize the state of its environment at that exact moment in time. You can think of it like pausing a car accident right before the cars connect, and walking around the scene while the whole world is paused, looking at everything trying to figure out what went wrong. Then, you can step through the scene, one second at a time, watching it play out in super slow motion.

This level of analysis is crucial in any space of problem solving. 

Software engineers build applications. You can think of applications like the engine of a car. They can be turned on and off, and when they are running, all of the individual components work together as one system. 

Car mechanics are essentially software engineers of the auto world. Once they choose a category (i.e. gas or electric), they run tests to identify the exact location in the running system where the problem is occurring. It’s the same concept as setting code breakpoints but in a different application.

A good image to think about when problem solving is a funnel. You begin at the widest part of the funnel, and get narrower as you explore, using the tactic of elimination to propel you deeper towards the smaller end. Choosing categories to test and explore will send you narrower into the funnel, and finding sub-categories within other categories will take you even further. 

