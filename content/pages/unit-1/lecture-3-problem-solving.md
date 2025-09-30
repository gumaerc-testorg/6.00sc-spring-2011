---
content_type: page
description: This section contains a lecture video and resources, lecture questions,
  and further study resources.
draft: true
learning_resource_types: []
ocw_type: CourseSection
parent_title: Unit 1
parent_type: CourseSection
parent_uid: 975ad7bf-dd9c-4ffe-26b6-710fa718d5e6
title: Problem Solving
uid: 3c3069d4-e0ed-fe69-ce4f-6de217d649a5
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---
« {{% resource_link 5a8ad51b-351a-4b3f-0c09-861452ea827d "Previous" %}} | {{% resource_link f13e5af9-52a2-f007-e596-f80bc01059fe "Next" %}} »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
{{< resource 2f3066e6-6ae1-2a9c-372a-73eed9c9372c >}}
{{< tdclose >}}
{{< tdopen >}}


This lecture covers the use of iteration to build programs whose execution time depends upon the size of inputs. It also introduces search problems and brute force and bisection for solving them.


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Activities
------------------

### Lecture Videos

*   {{% resource_link 3983511f-bf07-9526-cc8f-85e7e71ab634 "Lecture 3: Problem Solving" %}}

> ### About this Video
> 
> Topics covered: Termination, decrementing functions, exhaustive enumeration, brute force, while loop, for loop, approximation, specifications, bisection search.
> 
> ### Resources
> 
> *   {{% resource_link eba5e6fd-322a-f1ea-1ed8-26051df22062 "Lecture code handout (PDF)" %}}
> *   {{% resource_link f57eb256-134a-d5f0-9e1e-48ed205fad7f "Lecture code (PY)" %}}

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

*   {{% resource_link "758b1ca9-ed71-41d1-97c0-eedfebe76a1a" "Loops" %}}. An Introduction to Python.

« {{% resource_link 5a8ad51b-351a-4b3f-0c09-861452ea827d "Previous" %}} | {{% resource_link f13e5af9-52a2-f007-e596-f80bc01059fe "Next" %}} »