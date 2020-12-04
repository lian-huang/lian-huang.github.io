---
layout: essay
type: essay
title: Same Problems Same Solutions
date: 2020-12-03
labels:

---

### Becoming The Expert
Remember the times when you were tasked with a novice job, and it required you to do the same tasks over and over again? Maybe it was something simple like manually calculating numbers from a set of data or figuring out how to put together packets of information from separate piles of paper with the least amount of energy and time. Eventually, you figure out a good system for solving these problems and it takes less and less time the next time around. And when you figure out the pattern and how to become the most efficient at it, you become an expert and know exactly what to do every time after without having to go through the initial stages of figuring things out.

### Programer Edition
The same thing can be said for coding. Oftentimes, programmers run into the same problems in their coding or types of situations time and time again and end up coming with the same type of solution time and time again. But instead of having to fumble with it and spend time figuring it out, we can figure out the patterns and cut to the chase, the solution. Now, what if we expanded this to share these solutions with all other programmers out there so everyone can refer to the patterns and get to the solutions faster. Wouldn’t that save a lot of time and brain energy?! 

### The Observer Pattern
By reading patterns that others have solved, you can understand the problems other designers have had and the trade-offs. This significantly cuts down on documentation as others know what you are referring to. One design pattern I’ve used is the “Observer Pattern”. This pattern is seen in situations where one object must update itself whenever another particular object changes. The other object shouldn’t be complicated by code that explicitly sends notifications so one should have the subject object inherit from a superclass that maintains a list of observers. When the subject changes states it just calls one method and the observer implements an update() method to notify all the observers. This allows for each observer to register with the subject and when a change occurs, the subject notifies them all at the same time.

### Lava Flow
With design patterns, there are also anti-patterns. These should be avoided at all costs. One such anti-pattern is “Lava Flow”, this is generally classified as code that is usually hardcoded and forgotten in an environment with changing implementation. This is similar to an excel sheet that you hardcoded the numbers for, and when values are updated, you have to go through each cell to figure out if those values need to be updated instead of just cell referencing and the program automatically changing all the numbers at once. This anti-pattern gets its name from how molten lava turns to rock and is most likely not turning back into a lava anytime soon.  
