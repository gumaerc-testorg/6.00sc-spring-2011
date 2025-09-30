---
content_type: page
description: This section contains a lecture video and resources, lecture questions;
  problem set information, and further study resources.
draft: true
learning_resource_types: []
ocw_type: CourseSection
parent_title: Unit 2
parent_type: CourseSection
parent_uid: ddc5db7a-5c64-e3bd-a565-b36f4ed76287
title: Hashing and Classes
uid: 17410556-8f30-2907-b327-46f2da54236f
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---
« {{% resource_link ddc5db7a-5c64-e3bd-a565-b36f4ed76287 "Previous" %}} | {{% resource_link c7f4e874-e827-c2ec-07cb-6c920e3e1ee3 "Next" %}} »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
{{< resource 103553ac-9c66-5723-0fa2-3c613a1fb04a >}}
{{< tdclose >}}
{{< tdopen >}}


This lecture starts by showing how hashing can be used to achieve near constant time lookups and the concept of classes as understood by a computer. It then introduces exceptions.

_Image courtesy of {{% resource_link "92556409-d75d-4872-8fc0-82c054a746fe" "donovanbeeson" %}} on Flickr._


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Activities
------------------

### Lecture Videos

*   {{% resource_link d0e23d7c-4bd4-4024-7ba7-e3c0301e16c3 "Lecture 10: Hashing and Classes" %}}

> ### About this Video
> 
> Topics covered: Hashing, bucket, collision, linear rehash, exceptions, classes, modules, built-in classes.
> 
> ### Resources
> 
> *   {{% resource_link e299b670-216c-731c-44f1-a9038c495852 "Lecture code handout (PDF)" %}}
> *   {{% resource_link 5d63ea15-e55d-d11c-686a-aa83356206b0 "Lecture code (PY)" %}}

Check Yourself
--------------

What does hashing do?

{{< div-with-class "reveal1">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle1">}}

It converts the object to be hashed into an int that lies within a pre-defined range.

{{< /div-with-class >}}

What is a bucket?

{{< div-with-class "reveal2">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle2">}}

A list of items that have the same hash value.

{{< /div-with-class >}}

What are try blocks for?

{{< div-with-class "reveal3">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle3">}}

Try blocks are used when a piece of code may not work in all cases or for all inputs. It consists of a try statement and an except statement. First the try statement is executed; if it throws an exception, the program uses the except statement instead of terminating the program.

{{< /div-with-class >}}

What does polymorphic mean?

{{< div-with-class "reveal4">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle4">}}

Works with a variety of different types.

{{< /div-with-class >}}

What is a module?

{{< div-with-class "reveal5">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle5">}}

A collection of related functions.

{{< /div-with-class >}}

What is an object?

{{< div-with-class "reveal6">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle6">}}

A collection of data and functions that operate on that data.

{{< /div-with-class >}}

Problem Sets
------------

### Problem Set 4: The Caesar Cipher (Due)

This assignment will deal with a well-known (though not very secure) encryption method called the Caesar cipher. In this problem set you will need to devise your own algorithms and will practice using recursion to solve a non-trivial problem.

*   {{% resource_link ff50119b-d441-887d-641f-cdb569934b6d "Instructions (PDF)" %}}
*   {{% resource_link dc7676bd-ec5c-909f-89f9-43a4cd4043a9 "Pseudocode (PDF)" %}}
*   {{% resource_link 52f127bc-633a-8712-af2e-00487b1358ba "Code Files (ZIP)" %}} (This ZIP file contains: 1 .py file and 3 .txt files.)
*   {{% resource_link ba96a484-3a04-b800-6543-67757fe46d8c "Solutions (ZIP)" %}} (This ZIP file contains: 2 .py files.)

### Problem Set 5 (Assigned)

Problem set 5 is assigned in this session.  The instructions and solutions can be found on the session page where it is due, Lecture 12 {{% resource_link a7cc68bd-f5bd-3347-c014-209d6f7c9e17 "Introduction to Simulation and Random Walks" %}}.

Further Study
-------------

These optional resources are provided for students that wish to explore this topic more fully.

### Readings

After watching the lecture, you may want to read some of the following resources:

*   {{% resource_link "0ba53fcd-9cc9-45f0-ae7b-b6e1d14cf2d3" "12\. Classes and objects" %}}. How to Think Like a Computer Scientist.

### Related Lectures

*   [_6.006 Introduction to Algorithms_](/courses/6-006-introduction-to-algorithms-spring-2008). 6.006 lectures assume a greater level of mathematical sophistication than does 6.00SC. Read the lecture notes on:
    *   Hashing I: Chaining, hash functions
    *   Hashing II: Table doubling, Karp-Rabin
    *   Hashing III: Open addressing

« {{% resource_link ddc5db7a-5c64-e3bd-a565-b36f4ed76287 "Previous" %}} | {{% resource_link c7f4e874-e827-c2ec-07cb-6c920e3e1ee3 "Next" %}} »