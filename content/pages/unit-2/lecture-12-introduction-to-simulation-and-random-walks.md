---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: Unit 2
parent_type: CourseSection
parent_uid: ddc5db7a-5c64-e3bd-a565-b36f4ed76287
title: Introduction to Simulation and Random Walks
uid: a7cc68bd-f5bd-3347-c014-209d6f7c9e17
---

« [Previous]({{< baseurl >}}/pages/unit-2/lecture-11-oop-and-inheritance) | [Next]({{< baseurl >}}/pages/unit-2/lecture-13-some-basic-probability-and-plotting-data) »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
![Graph showing a movement trail from a random walk simulation.]({{< resource_file 381bd4c8-01da-26c7-934e-ea69c0324fda >}})
{{< tdclose >}}
{{< tdopen >}}


This lecture completes the introduction of classes by showing a way to implement user-defined iterators. It then discusses simulation models, and illustrates some of the ideas underlying simulations modeling by simulating a random walk.

_Image courtesy of [donovanbeeson](http://www.flickr.com/photos/donovan_beeson/5792363110/) on Flickr._


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Activities
------------------

### Lecture Videos

*   [Lecture 12: Introduction to Simulation and Random Walks]({{< baseurl >}}/resources/lecture-12-introduction-to-simulation-and-random-walks)

> ### About this Video
> 
> Topics covered: Subclasses, inheritance, generator, analytic methods, simulation methods, simulations, models, random walk.
> 
> ### Resources
> 
> *   [Lecture code handout (PDF)]({{< baseurl >}}/resources/mit6_00scs11_lec12)
> *   [Lecture code (PY)]({{< baseurl >}}/resources/lec12)

Check Yourself
--------------

What is a generator?

{{< div-with-class "reveal1">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle1">}}

A function that remembers the point in the function body where it last returned a value and the values of all local variables.

{{< /div-with-class >}}

What is the difference between yield and return?

{{< div-with-class "reveal2">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle2">}}

When yield is used, the state of the function is not lost.

{{< /div-with-class >}}

What is a model?

{{< div-with-class "reveal3">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle3">}}

A model is a theoretical construct that will provide useful information about the possible behaviors of the system being modeled.

{{< /div-with-class >}}

Problem Sets
------------

### Problem Set 5: RSS Feed Filter (Due)

In problem set 5, you will build a program to monitor news feeds over the Internet. Your program will filter the news, alerting the user when it notices a news story that matches that user's interests (for example, the user may be interested in a notification whenever a story related to the Red Sox is posted).

*   [Instructions (PDF)]({{< baseurl >}}/resources/mit6_00scs11_ps5)
*   [Code Files (ZIP)]({{< baseurl >}}/resources/ps5) (This file contains 1 .txt file, 3 .pyc files, and 6 .py files.)
*   [Solutions (ZIP)]({{< baseurl >}}/resources/ps5_sol) (This ZIP file contains: 1 .py file.)

### Problem Set 6 (Assigned)

Problem set 6 is assigned in this session. The instructions and solutions can be found on the session page where it is due, Lecture 14 [Sampling and Monte Carlo Simulation]({{< baseurl >}}/pages/unit-2/lecture-14-sampling-and-monte-carlo-simulation).

« [Previous]({{< baseurl >}}/pages/unit-2/lecture-11-oop-and-inheritance) | [Next]({{< baseurl >}}/pages/unit-2/lecture-13-some-basic-probability-and-plotting-data) »