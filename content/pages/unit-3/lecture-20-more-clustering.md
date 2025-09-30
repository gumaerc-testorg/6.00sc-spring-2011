---
content_type: page
description: This section contains a lecture video and resources, recitation video,
  lecture questions, and problem set information.
draft: true
learning_resource_types: []
ocw_type: CourseSection
parent_title: Unit 3
parent_type: CourseSection
parent_uid: 82c15099-81b2-70b9-823b-c741f08c9b32
title: More Clustering
uid: fc440c95-aa3e-3ffa-8cff-14461dc75eee
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---
« {{% resource_link 82c15099-81b2-70b9-823b-c741f08c9b32 "Previous" %}} | {{% resource_link e1b5ff21-127d-fb30-33e3-98fce88c42e6 "Next" %}} »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
{{< resource 83badeff-3504-8cca-4372-f5bd8d5d19b8 >}}
{{< tdclose >}}
{{< tdopen >}}


This lecture covers hierarchical clustering and introduces k-means clustering.

_This image is from the {{% resource_link "0e77f3cd-5662-410a-beca-03448a0b4a33" "Wikimedia Commons" %}}. This image is in the public domain._


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Activities
------------------

### Lecture Videos

*   {{% resource_link 8e437d60-4662-11a1-b9ed-6bd1be497165 "Lecture 20: More Clustering" %}}

> ### About this Video
> 
> Topics covered: Feature vectors, scaling, k-means clustering.
> 
> ### Resources
> 
> *   {{% resource_link 60df582d-4c81-2a78-7695-952b65aced83 "Lecture code handout (PDF)" %}}
> *   {{% resource_link 5c2ca116-1808-cbe2-ec41-f8000773ad78 "Lecture code (PY)" %}}
> *   {{% resource_link e09f895c-c2c0-3cc0-7388-e4440df7b2f7 "Lecture slides (PDF)" %}}
> *   {{% resource_link 825878e7-db0c-30e1-d516-d3281c251d4c "Lecture data files (ZIP)" %}} (This ZIP file contains: 3 .txt files.)

### Recitation Videos

*   {{% resource_link bf184146-83d1-aed8-d65a-2d4b8b584cc0 "Recitation 8: Hierarchical and k-means Clustering" %}}

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

*   {{% resource_link 74fa9ea1-abae-236f-3f06-15f8ec039e39 "Instructions (PDF)" %}}
*   {{% resource_link 6dcb99ce-9c44-a3b5-64dc-9d6177f4a831 "Code Files (ZIP)" %}} (This ZIP file contains: 2 .py files and 2 .txt files.)

_Note: Solutions are not available for this assignment._

### Problem Set 10 (Assigned)

Problem set 10 is assigned in this session.  The instructions and solutions can be found on the session page where it is due, Lecture 22 {{% resource_link d4f15989-167b-6654-ef5c-a2931d758afd "Using Graphs to Model Problems, Part 2" %}}.

« {{% resource_link 82c15099-81b2-70b9-823b-c741f08c9b32 "Previous" %}} | {{% resource_link e1b5ff21-127d-fb30-33e3-98fce88c42e6 "Next" %}} »