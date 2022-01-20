---
content_type: page
parent_title: Unit 3
parent_uid: 82c15099-81b2-70b9-823b-c741f08c9b32
title: More Clustering
uid: fc440c95-aa3e-3ffa-8cff-14461dc75eee
---

« [Previous]({{< baseurl >}}/pages/unit-3) | [Next]({{< baseurl >}}/pages/unit-3/lecture-21-using-graphs-to-model-problems-part-1) »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
![ses-20.jpg]({{< resource_file 83badeff-3504-8cca-4372-f5bd8d5d19b8 >}})
{{< tdclose >}}
{{< tdopen >}}


This lecture covers hierarchical clustering and introduces k-means clustering.

_This image is from the [Wikimedia Commons](http://en.wikipedia.org/wiki/File:Manhattan_distance.svg). This image is in the public domain._


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Activities
------------------

### Lecture Videos

*   [Lecture 20: More Clustering]({{< baseurl >}}/resources/lecture-20-more-clustering)

> ### About this Video
> 
> Topics covered: Feature vectors, scaling, k-means clustering.
> 
> ### Resources
> 
> *   [Lecture code handout (PDF)]({{< baseurl >}}/resources/mit6_00scs11_lec20)
> *   [Lecture code (PY)]({{< baseurl >}}/resources/lec20)
> *   [Lecture slides (PDF)]({{< baseurl >}}/resources/mit6_00scs11_lec20_slides)
> *   [Lecture data files (ZIP)]({{< baseurl >}}/resources/lec20_data) (This ZIP file contains: 3 .txt files.)

### Recitation Videos

*   [Recitation 8: Hierarchical and k-means Clustering]({{< baseurl >}}/resources/recitation-8-hierarchical-and-k-means-clustering)

> ### About this Video
> 
> Topics covered: Unsupervised learning, k-means clustering, distance metric, cluster merging, centroid, k-mean error, holdout set, k value significance, features of k-means clustering, merits and disadvantages of types of clustering.

Check Yourself
--------------

How do we use nominal (non-numeric or noncontinuous) categories as features?

{{< div-with-class "reveal1">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle1">}}

Convert each possible value to a real number.

{{< /div-with-class >}}

Why do we need to use scaling (normalization)?

{{< div-with-class "reveal2">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle2">}}

To indicate the relative importance of each feature.

{{< /div-with-class >}}

How does k-means clustering work?

{{< div-with-class "reveal3">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle3">}}

A number 'k' points are chosen, randomly or otherwise, to be the initial centroids; all other points are assigned to their nearest centroid. A new, better centroid is then chosen for each cluster, and we rinse and repeat until the difference between our current set of clusters and the previous set is insignificant.

{{< /div-with-class >}}

Problem Sets
------------

### Problem Set 9: Schedule Optimization (Due)

At an institute of higher education that shall remain nameless, it used to be the case that a human adviser would help each student formulate a list of subjects that would meet the student's objectives. However, because of financial troubles, the Institute has decided to replace human advisers with software. Given the amount of work a student wants to do, the program returns a list of subjects that maximizes the amount of value. The goal of this problem set is to implement optimization algorithms.

*   [Instructions (PDF)]({{< baseurl >}}/resources/mit6_00scs11_ps9)
*   [Code Files (ZIP)]({{< baseurl >}}/resources/ps9) (This ZIP file contains: 2 .py files and 2 .txt files.)

_Note: Solutions are not available for this assignment._

### Problem Set 10 (Assigned)

Problem set 10 is assigned in this session.  The instructions and solutions can be found on the session page where it is due, Lecture 22 [Using Graphs to Model Problems, Part 2]({{< baseurl >}}/pages/unit-3/lecture-22-using-graphs-to-model-problems-part-2).

« [Previous]({{< baseurl >}}/pages/unit-3) | [Next]({{< baseurl >}}/pages/unit-3/lecture-21-using-graphs-to-model-problems-part-1) »