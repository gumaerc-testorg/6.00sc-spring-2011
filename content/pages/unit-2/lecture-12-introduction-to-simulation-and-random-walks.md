---
content_type: page
description: This section contains a lecture video and resources, recitation video,
  lecture questions, and problem set information.
learning_resource_types: []
ocw_type: CourseSection
parent_title: Unit 2
parent_type: CourseSection
parent_uid: ddc5db7a-5c64-e3bd-a565-b36f4ed76287
title: Introduction to Simulation and Random Walks
uid: a7cc68bd-f5bd-3347-c014-209d6f7c9e17
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

« {{% resource_link c7f4e874-e827-c2ec-07cb-6c920e3e1ee3 "Previous" %}} | {{% resource_link fbfa6485-7038-d1fe-9497-74c45d99d5e0 "Next" %}} »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
{{< resource 381bd4c8-01da-26c7-934e-ea69c0324fda >}}
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

*   {{% resource_link 96823d86-e5ec-ea67-fe3c-3826c9060125 "Lecture 12: Introduction to Simulation and Random Walks" %}}

> ### About this Video
> 
> Topics covered: Subclasses, inheritance, generator, analytic methods, simulation methods, simulations, models, random walk.
> 
> ### Resources
> 
> *   {{% resource_link 9ce2e34d-1f23-04d0-432d-e82606cf7dd4 "Lecture code handout (PDF)" %}}
> *   {{% resource_link d8fb636c-96ac-62b1-b56f-554a8125bdcc "Lecture code (PY)" %}}

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

*   {{% resource_link 8750511b-8667-36cb-916f-ad0b5e7d96b0 "Instructions (PDF)" %}}
*   {{% resource_link 6a8d6217-ad4f-264b-9a31-2d05bb6d430e "Code Files (ZIP)" %}} (This file contains 1 .txt file, 3 .pyc files, and 6 .py files.)
*   {{% resource_link 052cd678-1574-3abf-7f40-6dfbb50112a0 "Solutions (ZIP)" %}} (This ZIP file contains: 1 .py file.)

### Problem Set 6 (Assigned)

Problem set 6 is assigned in this session. The instructions and solutions can be found on the session page where it is due, Lecture 14 {{% resource_link eb6bcb74-e4a6-c927-a72e-0bf586910c4c "Sampling and Monte Carlo Simulation" %}}.

« {{% resource_link c7f4e874-e827-c2ec-07cb-6c920e3e1ee3 "Previous" %}} | {{% resource_link fbfa6485-7038-d1fe-9497-74c45d99d5e0 "Next" %}} »