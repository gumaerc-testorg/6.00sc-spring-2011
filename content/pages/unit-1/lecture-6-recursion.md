---
content_type: page
description: This section contains a lecture video and resources, recitation video,
  lecture questions, problem set information, and further study resources.
draft: true
learning_resource_types: []
ocw_type: CourseSection
parent_title: Unit 1
parent_type: CourseSection
parent_uid: 975ad7bf-dd9c-4ffe-26b6-710fa718d5e6
title: Recursion
uid: 99fb7e49-022e-2ef5-90b8-a591159332ed
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---
« {{% resource_link 138c881e-91b6-6b62-fdc8-2ea403e07fc5 "Previous" %}} | {{% resource_link ebde421e-0808-fd28-3195-0f1a9a69cfb3 "Next" %}} »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
{{< resource a036c17d-569b-bbf7-38e6-36b64f1457d3 >}}
{{< tdclose >}}
{{< tdopen >}}


This lecture finishes the discussion of dictionaries, then introduces inductive reasoning and recursion. Examples include generating the Fibonacci sequence and solving the Towers of Hanoi problem.

_Image courtesy of {{% resource_link "20c49c49-c9f7-4e24-ae5e-5dea25a5a575" "Stephen & Claire Farnsworth" %}} on Flickr._


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Activities
------------------

### Lecture Videos

*   {{% resource_link 6f175d89-5f9c-6355-2ca8-8c3cef056c58 "Lecture 6: Recursion" %}}

> ### About this Video
> 
> Topics covered: Dictionaries, modular abstraction, divide and conquer, recursion, tower of Hanoi, base case, Fibonacci sequence.
> 
> ### Resources
> 
> *   {{% resource_link c49ccca5-6967-1754-141d-71e5aad25323 "Lecture code handout (PDF)" %}}
> *   {{% resource_link 47eb6084-78d8-fb1e-d999-357c3b2fec8c "Lecture code (PY)" %}}

### Recitation Videos

*   {{% resource_link 97977763-b598-d90b-e991-0e0e7b258383 "Recitation 3: Lists and their Elements, Sorting, and Recursion" %}}

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

*   {{% resource_link 3a5ebc03-9238-f675-c60e-c1a490096b18 "Instructions (PDF)" %}}
*   {{% resource_link 4bafc5d1-520e-9d88-5e18-766b1c4ef47d "Code Files (ZIP)" %}} (This ZIP file contains: 1 .txt file and 2 .py files.)
*   {{% resource_link b3906376-71a6-0cd6-6e95-644963b523fd "Solutions (ZIP)" %}} (This ZIP file contains: 3 .py files.)

### Problem Set 3 (Assigned)

Problem set 3 is assigned in this session. The instructions and solutions can be found on the session page where it is due, Lecture 7 {{% resource_link ebde421e-0808-fd28-3195-0f1a9a69cfb3 "Debugging" %}}.

Further Study
-------------

These optional resources are provided for students that wish to explore this topic more fully.

### Readings

After watching the lecture, you may want to read some of the following resources:

*   {{% resource_link "128c764a-5499-43e8-8839-4fd3f892ce87" "4.9 Recursion" %}}. How to Think Like a Computer Scientist.
*   {{% resource_link "7761b5e1-fdce-4d81-89b6-7d41a38fd62d" "Recursion" %}}. An Introduction to Python.
*   {{% resource_link "a5bd2d0e-d604-487e-9331-3a3b9424f160" "Comparing Recursion and Looping" %}}. An Introduction to Python.

### Related Lectures

*   [_6.006 Introduction to Algorithms_](/courses/6-006-introduction-to-algorithms-spring-2008). 6.006 lectures assume a greater level of mathematical sophistication than does 6.00SC. Read the lecture notes on:
    *   Dynamic programming I: memoization, Fibonacci, Crazy Eights, guessing

« {{% resource_link 138c881e-91b6-6b62-fdc8-2ea403e07fc5 "Previous" %}} | {{% resource_link ebde421e-0808-fd28-3195-0f1a9a69cfb3 "Next" %}} »