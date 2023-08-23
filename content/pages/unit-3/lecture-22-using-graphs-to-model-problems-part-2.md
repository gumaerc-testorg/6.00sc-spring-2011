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
title: Using Graphs to Model Problems, Part 2
uid: d4f15989-167b-6654-ef5c-a2931d758afd
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---
« {{% resource_link e1b5ff21-127d-fb30-33e3-98fce88c42e6 "Previous" %}} | {{% resource_link 142ece9e-e56e-5c28-8b69-1c969251db2d "Next" %}} »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
{{< resource c10820c3-cb9d-e8eb-b479-cacc401976a3 >}}
{{< tdclose >}}
{{< tdopen >}}


This lecture returns to graph theory. It defines and gives examples of some classic graph problems: shortest path, shortest weighted path, cliques, and min-cut. It then shows how memoization can be used to speed up some algorithms.

_[Centers for Disease Control and Prevention](http://www.cdc.gov/). This image is in the public domain._


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Activities
------------------

### Lecture Videos

*   {{% resource_link b018e786-d7a7-dbb3-271f-f580bce89f28 "Lecture 22: Using Graphs to Model Problems, Part 2" %}}

> ### About this Video
> 
> Topics covered: Dynamic programming, optimal path, overlapping subproblems, weighted edges, specifications, restrictions, efficiency, pseudo-polynomials.
> 
> ### Resources
> 
> *   {{% resource_link e8d25aca-0330-9909-7b9e-71b5a63bb4e1 "Lecture code handout (PDF)" %}}
> *   {{% resource_link dc7d1685-ab8b-22d2-f31d-132be9f2ce46 "Lecture code (PY)" %}}

### Recitation Videos

*   {{% resource_link 39d373cb-273f-5626-fae4-c26a850208f1 "Recitation 9: Directed and Undirected Node Graphs" %}}

> ### About this Video
> 
> Topics covered: Node graphs, nodes, edges, directed and undirected graphs, weighted edges, depth-first search, breadth-first search, graph cycles, children of nodes, shortest path, lambda functions.

Check Yourself
--------------

What is memoization?

{{< div-with-class "reveal1">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle1">}}

Memoization involves saving work that we've done to a table, so that in the future, we can look it up rather than recalculating.

{{< /div-with-class >}}

Why is memoization important?

{{< div-with-class "reveal2">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle2">}}

It helps us avoid redoing work that we have already done, thereby making programs more efficient. It is the key idea behind the programming techniques known as dynamic programming.

{{< /div-with-class >}}

Problem Sets
------------

### Problem Set 10: Clustering (Due)

Every decade, the United States Census takes place. The census collects a lot of information from the population around the United States. In this problem set, we are going to use k-means clustering to analyze this information.

*   {{% resource_link f453001f-3ce9-20aa-14ea-e9b218186626 "Instructions (PDF)" %}}
*   {{% resource_link 5dba9703-f559-a272-4c9e-9f50dd807550 "Code Files (ZIP)" %}} (This ZIP file contains: 1 .py file and 1 .txt file.)

_Note: Solutions are not available for this assignment._

### Problem Set 11 (Assigned)

Problem set 11 is assigned in this session. The instructions and solutions can be found on the session page where it is due, Lecture 24 {{% resource_link 1516a60b-ecbc-5b34-fa72-5b89a5ef9a21 "Avoiding Statistical Fallacies" %}}.

« {{% resource_link e1b5ff21-127d-fb30-33e3-98fce88c42e6 "Previous" %}} | {{% resource_link 142ece9e-e56e-5c28-8b69-1c969251db2d "Next" %}} »