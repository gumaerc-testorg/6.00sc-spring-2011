---
content_type: page
parent_title: Unit 1
parent_uid: 975ad7bf-dd9c-4ffe-26b6-710fa718d5e6
title: Problem Solving
uid: 3c3069d4-e0ed-fe69-ce4f-6de217d649a5
---

« [Previous]({{< baseurl >}}/pages/unit-1/lecture-2-core-elements-of-a-program) | [Next]({{< baseurl >}}/pages/unit-1/lecture-4-machine-interpretation-of-a-program) »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
![Image of mathematical operators, (+ - / x).]({{< resource_file 2f3066e6-6ae1-2a9c-372a-73eed9c9372c >}})
{{< tdclose >}}
{{< tdopen >}}


This lecture covers the use of iteration to build programs whose execution time depends upon the size of inputs. It also introduces search problems and brute force and bisection for solving them.


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Activities
------------------

### Lecture Videos

*   [Lecture 3: Problem Solving]({{< baseurl >}}/resources/lecture-3-problem-solving)

> ### About this Video
> 
> Topics covered: Termination, decrementing functions, exhaustive enumeration, brute force, while loop, for loop, approximation, specifications, bisection search.
> 
> ### Resources
> 
> *   [Lecture code handout (PDF)]({{< baseurl >}}/resources/mit6_00scs11_lec03)
> *   [Lecture code (PY)]({{< baseurl >}}/resources/lec03)

Check Yourself
--------------

What does it mean for a program to terminate?

{{< div-with-class "reveal1">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle1">}}

Either the program will return a value, or throw an exception. A program that does not terminate runs indefinitely, typically because it's gotten stuck in a loop.

{{< /div-with-class >}}

What is a for loop?

{{< div-with-class "reveal2">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle2">}}

A for loop takes some sort of iterable object (a list, tuple, or string) and performs its function once for each item in that object. Any function that depends on the input can have a different result at each step, since the input is the current item.

{{< /div-with-class >}}

Further Study
-------------

These optional resources are provided for students that wish to explore this topic more fully.

### Readings

*   [Loops](https://opentechschool.github.io/python-beginners/en/loops.html). An Introduction to Python.

« [Previous]({{< baseurl >}}/pages/unit-1/lecture-2-core-elements-of-a-program) | [Next]({{< baseurl >}}/pages/unit-1/lecture-4-machine-interpretation-of-a-program) »