---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: Unit 1
parent_type: CourseSection
parent_uid: 975ad7bf-dd9c-4ffe-26b6-710fa718d5e6
title: Debugging
uid: ebde421e-0808-fd28-3195-0f1a9a69cfb3
---

« [Previous]({{< baseurl >}}/pages/unit-1/lecture-6-recursion) | [Next]({{< baseurl >}}/pages/unit-1/lecture-8-efficiency-and-order-of-growth) »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
![Photograph of a moth taped into a lab notebook.]({{< resource_file 3a7a598d-97e4-1758-6fed-83ef1189049b >}})
{{< tdclose >}}
{{< tdopen >}}


This lecture starts with a brief explanation of why floating point numbers are only an approximation of the real numbers. Most of the lecture is about a systematic approach to debugging.

_Image courtesy of the [Naval Surface Warfare Center](https://www.navsea.navy.mil/Home/Warfare-Centers/NSWC-Dahlgren/), Dahlgren, VA._


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Activities
------------------

### Lecture Videos

*   [Lecture 7: Debugging]({{< baseurl >}}/resources/lecture-7-debugging)

> ### About this Video
> 
> Topics covered: Binary, float, floating point, approximations, debugging, runtime error.
> 
> ### Resources
> 
> *   [Lecture code handout (PDF)]({{< baseurl >}}/resources/mit6_00scs11_lec07)
> *   [Lecture code (PY)]({{< baseurl >}}/resources/lec07)
> *   [Lecture slides (PDF)]({{< baseurl >}}/resources/mit6_00scs11_lec07_slides)

### Recitation Videos

*   [Recitation 4: Recursion, Pseudo code and Debugging]({{< baseurl >}}/resources/recitation-4-recursion-pseudo-code-and-debugging)

> _About this Video_
> 
> Topics covered: Recursion, divide and conquer, base cases, iterative vs. recursive algorithms, Fibonacci numbers example, recursive bisection search, optional and default parameters, pseudo code, introduction to debugging, test cases and edge cases, and floating points.

Check Yourself
--------------

Why do computers use binary representations?

{{< div-with-class "reveal1">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle1">}}

It's easy to build hardware with two states, on and off.

{{< /div-with-class >}}

Why shouldn't we test for equality with floats?

{{< div-with-class "reveal2">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle2">}}

Because computers use binary, floats are actually very close approximations of the actual values. Testing for equality can result in an unexpected error, so it's better to determine whether two numbers are close enough for our purposes rather than precisely equal.

{{< /div-with-class >}}

When debugging, how can you ensure that the values in your program are the ones you think they are?

{{< div-with-class "reveal3">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle3">}}

Use print statements.

{{< /div-with-class >}}

Problem Sets
------------

### Problem Set 3: Wordgames (Due)

In this problem set, you'll implement _two_ versions of the 6.00 wordgame! Don't be intimidated by the length of this problem set. It's a lot of reading, but it is very doable.

Let's begin by describing the 6.00 wordgame: This game is a lot like Scrabble or Text Twist, if you've played those. Letters are dealt to players, who then construct one or more words out of their letters. Each **valid** word receives a score, based on the length of the word and the letters in that word.

*   [Instructions (PDF)]({{< baseurl >}}/resources/mit6_00scs11_ps3)
*   [Code files (ZIP)]({{< baseurl >}}/resources/ps3) (This ZIP file contains: 1 .txt file and 4 .py files.)
*   [Solutions (ZIP)]({{< baseurl >}}/resources/ps3_sol) (This ZIP file contains: 2 .py files.)

### Problem Set 4 (Assigned)

Problem set 4 is assigned in this session. The instructions and solutions can be found on the session page where it is due, Lecture 10 [Hashing and Classes]({{< baseurl >}}/pages/unit-2/lecture-10-hashing-and-classes).

Further Study
-------------

These optional resources are provided for students that wish to explore this topic more fully.

### Readings

After watching the lecture, you may want to read some of the following resources:

*   [8\. Errors and Exceptions](http://docs.python.org/tutorial/errors.html). Python Tutorial.
*   [Appendix A: Debugging](http://www.greenteapress.com/thinkpython/thinkCSpy/html/app01.html). How to Think Like a Computer Scientist.

« [Previous]({{< baseurl >}}/pages/unit-1/lecture-6-recursion) | [Next]({{< baseurl >}}/pages/unit-1/lecture-8-efficiency-and-order-of-growth) »