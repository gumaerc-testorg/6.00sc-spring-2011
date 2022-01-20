---
content_type: page
parent_title: Unit 1
parent_uid: 975ad7bf-dd9c-4ffe-26b6-710fa718d5e6
title: Recursion
uid: 99fb7e49-022e-2ef5-90b8-a591159332ed
---

« [Previous]({{< baseurl >}}/pages/unit-1/lecture-5-objects-in-python) | [Next]({{< baseurl >}}/pages/unit-1/lecture-7-debugging) »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
![Photograph of a rabbit.]({{< resource_file a036c17d-569b-bbf7-38e6-36b64f1457d3 >}})
{{< tdclose >}}
{{< tdopen >}}


This lecture finishes the discussion of dictionaries, then introduces inductive reasoning and recursion. Examples include generating the Fibonacci sequence and solving the Towers of Hanoi problem.

_Image courtesy of [Stephen & Claire Farnsworth](http://www.flickr.com/photos/the_farnsworths/5808550435/in/photostream/) on Flickr._


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Activities
------------------

### Lecture Videos

*   [Lecture 6: Recursion]({{< baseurl >}}/resources/lecture-6-recursion)

> ### About this Video
> 
> Topics covered: Dictionaries, modular abstraction, divide and conquer, recursion, tower of Hanoi, base case, Fibonacci sequence.
> 
> ### Resources
> 
> *   [Lecture code handout (PDF)]({{< baseurl >}}/resources/mit6_00scs11_lec06)
> *   [Lecture code (PY)]({{< baseurl >}}/resources/lec06)

### Recitation Videos

*   [Recitation 3: Lists and their Elements, Sorting, and Recursion]({{< baseurl >}}/resources/recitation-3-lists-and-their-elements-sorting-and-recursion)

> ### About this Video
> 
> Topics covered: Tuples, lists, iteration, list elements, sorting lists, mutability, keys, dictionaries, chain method, recursion, base case, Tower of Hanoi.

Check Yourself
--------------

What is recursion?

{{< div-with-class "reveal1">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle1">}}

Recursion, or "divide-and-conquer", allows us to define a function that calls itself to solve a problem by breaking it into simpler cases.

{{< /div-with-class >}}

What is a recursive case?

{{< div-with-class "reveal2">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle2">}}

A recursive case calls the recursive procedure on a simpler case (usually a part of the input).

{{< /div-with-class >}}

What is a base case?

{{< div-with-class "reveal3">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle3">}}

A base case is necessary in recursion; it determines when the procedure returns a value (or terminates), rather than continuing the recursive process.

{{< /div-with-class >}}

Problem Sets
------------

### Problem Set 2: Successive Approximation and a Wordgame (Due)

Successive approximation is a problem-solving method where you try to guess the right answer to a problem and then check your guess. If the guess is good enough, you're done. Otherwise, you keep improving your guess in small increments and checking it, getting closer and closer to the right answer, until you determine that the guess is good enough. For the first 3 problems of this problem set, we will look at Newton's method, which uses successive approximation to find the roots of a function.

Secondly, we will have some fun with Python, and get some practice using strings and string operations. We would like you to implement the word game Hangman as a 1-player game against the computer.

*   [Instructions (PDF)]({{< baseurl >}}/resources/mit6_00scs11_ps2)
*   [Code Files (ZIP)]({{< baseurl >}}/resources/ps2) (This ZIP file contains: 1 .txt file and 2 .py files.)
*   [Solutions (ZIP)]({{< baseurl >}}/resources/ps2_sol) (This ZIP file contains: 3 .py files.)

### Problem Set 3 (Assigned)

Problem set 3 is assigned in this session. The instructions and solutions can be found on the session page where it is due, Lecture 7 [Debugging]({{< baseurl >}}/pages/unit-1/lecture-7-debugging).

Further Study
-------------

These optional resources are provided for students that wish to explore this topic more fully.

### Readings

After watching the lecture, you may want to read some of the following resources:

*   [4.9 Recursion](http://www.greenteapress.com/thinkpython/thinkCSpy/html/chap04.html). How to Think Like a Computer Scientist.
*   [Recursion](http://www.slideshare.net/dtinth/introduction-to-recursion-python). An Introduction to Python.
*   [Comparing Recursion and Looping](http://troll.cs.ua.edu/ACP-PY/index_18.html). An Introduction to Python.

### Related Lectures

*   [_6.006 Introduction to Algorithms_](/courses/6-006-introduction-to-algorithms-spring-2008/). 6.006 lectures assume a greater level of mathematical sophistication than does 6.00SC. Read the lecture notes on:
    *   Dynamic programming I: memoization, Fibonacci, Crazy Eights, guessing

« [Previous]({{< baseurl >}}/pages/unit-1/lecture-5-objects-in-python) | [Next]({{< baseurl >}}/pages/unit-1/lecture-7-debugging) »