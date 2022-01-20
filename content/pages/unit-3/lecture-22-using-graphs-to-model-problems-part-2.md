---
content_type: page
parent_title: Unit 3
parent_uid: 82c15099-81b2-70b9-823b-c741f08c9b32
title: Using Graphs to Model Problems, Part 2
uid: d4f15989-167b-6654-ef5c-a2931d758afd
---

« [Previous]({{< baseurl >}}/pages/unit-3/lecture-21-using-graphs-to-model-problems-part-1) | [Next]({{< baseurl >}}/pages/unit-3/lecture-23-dynamic-programming) »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
![ses-22.jpg]({{< resource_file c10820c3-cb9d-e8eb-b479-cacc401976a3 >}})
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

*   [Lecture 22: Using Graphs to Model Problems, Part 2]({{< baseurl >}}/resources/lecture-22-using-graphs-to-model-problems-part-2)

> ### About this Video
> 
> Topics covered: Dynamic programming, optimal path, overlapping subproblems, weighted edges, specifications, restrictions, efficiency, pseudo-polynomials.
> 
> ### Resources
> 
> *   [Lecture code handout (PDF)]({{< baseurl >}}/resources/mit6_00scs11_lec22)
> *   [Lecture code (PY)]({{< baseurl >}}/resources/lec22)

### Recitation Videos

*   [Recitation 9: Directed and Undirected Node Graphs]({{< baseurl >}}/resources/recitation-9-directed-and-undirected-node-graphs)

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

*   [Instructions (PDF)]({{< baseurl >}}/resources/mit6_00scs11_ps10)
*   [Code Files (ZIP)]({{< baseurl >}}/resources/ps10) (This ZIP file contains: 1 .py file and 1 .txt file.)

_Note: Solutions are not available for this assignment._

### Problem Set 11 (Assigned)

Problem set 11 is assigned in this session. The instructions and solutions can be found on the session page where it is due, Lecture 24 [Avoiding Statistical Fallacies]({{< baseurl >}}/pages/unit-3/lecture-24-avoiding-statistical-fallacies).

« [Previous]({{< baseurl >}}/pages/unit-3/lecture-21-using-graphs-to-model-problems-part-1) | [Next]({{< baseurl >}}/pages/unit-3/lecture-23-dynamic-programming) »