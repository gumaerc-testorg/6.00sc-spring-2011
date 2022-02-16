---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: Unit 2
parent_type: CourseSection
parent_uid: ddc5db7a-5c64-e3bd-a565-b36f4ed76287
title: Hashing and Classes
uid: 17410556-8f30-2907-b327-46f2da54236f
---

« [Previous]({{< baseurl >}}/pages/unit-2) | [Next]({{< baseurl >}}/pages/unit-2/lecture-11-oop-and-inheritance) »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
![Photograph of a box of air mail envelopes.]({{< resource_file 103553ac-9c66-5723-0fa2-3c613a1fb04a >}})
{{< tdclose >}}
{{< tdopen >}}


This lecture starts by showing how hashing can be used to achieve near constant time lookups and the concept of classes as understood by a computer. It then introduces exceptions.

_Image courtesy of [donovanbeeson](http://www.flickr.com/photos/donovan_beeson/5792363110/) on Flickr._


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Activities
------------------

### Lecture Videos

*   [Lecture 10: Hashing and Classes]({{< baseurl >}}/resources/lecture-10-hashing-and-classes)

> ### About this Video
> 
> Topics covered: Hashing, bucket, collision, linear rehash, exceptions, classes, modules, built-in classes.
> 
> ### Resources
> 
> *   [Lecture code handout (PDF)]({{< baseurl >}}/resources/mit6_00scs11_lec10)
> *   [Lecture code (PY)]({{< baseurl >}}/resources/lec10)

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

*   [Instructions (PDF)]({{< baseurl >}}/resources/mit6_00scs11_ps4)
*   [Pseudocode (PDF)]({{< baseurl >}}/resources/mit6_00scs11_ps4-pseudo)
*   [Code Files (ZIP)]({{< baseurl >}}/resources/ps4) (This ZIP file contains: 1 .py file and 3 .txt files.)
*   [Solutions (ZIP)]({{< baseurl >}}/resources/ps4_sol) (This ZIP file contains: 2 .py files.)

### Problem Set 5 (Assigned)

Problem set 5 is assigned in this session.  The instructions and solutions can be found on the session page where it is due, Lecture 12 [Introduction to Simulation and Random Walks]({{< baseurl >}}/pages/unit-2/lecture-12-introduction-to-simulation-and-random-walks).

Further Study
-------------

These optional resources are provided for students that wish to explore this topic more fully.

### Readings

After watching the lecture, you may want to read some of the following resources:

*   [12\. Classes and objects](http://www.greenteapress.com/thinkpython/thinkCSpy/html/chap12.html). How to Think Like a Computer Scientist.

### Related Lectures

*   [_6.006 Introduction to Algorithms_](/courses/6-006-introduction-to-algorithms-spring-2008/). 6.006 lectures assume a greater level of mathematical sophistication than does 6.00SC. Read the lecture notes on:
    *   Hashing I: Chaining, hash functions
    *   Hashing II: Table doubling, Karp-Rabin
    *   Hashing III: Open addressing

« [Previous]({{< baseurl >}}/pages/unit-2) | [Next]({{< baseurl >}}/pages/unit-2/lecture-11-oop-and-inheritance) »