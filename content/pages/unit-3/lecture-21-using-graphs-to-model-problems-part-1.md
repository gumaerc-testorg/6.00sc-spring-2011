---
content_type: page
parent_title: Unit 3
parent_uid: 82c15099-81b2-70b9-823b-c741f08c9b32
title: Using Graphs to Model Problems, Part 1
uid: e1b5ff21-127d-fb30-33e3-98fce88c42e6
---

« [Previous]({{< baseurl >}}/pages/unit-3/lecture-20-more-clustering) | [Next]({{< baseurl >}}/pages/unit-3/lecture-22-using-graphs-to-model-problems-part-2) »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
![ses-21.jpg]({{< resource_file 60ac9bba-264e-4869-5fd6-4a52189ef432 >}})
{{< tdclose >}}
{{< tdopen >}}


This lecture begins by finishing up k-means clustering. It then moves on to introduce the notion of modeling things using graphs (sets of nodes and edges that link them).


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Activities
------------------

### Lecture Videos

*   [Lecture 21: Using Graphs to Model Problems, Part 1]({{< baseurl >}}/resources/lecture-21-using-graphs-to-model-problems-part-1)

> ### About this Video
> 
> Topics covered: Pseudocode, graphs, nodes, edges, adjacency matrix, adjacency list.
> 
> ### Resources
> 
> *   [Lecture code handout (PDF)]({{< baseurl >}}/resources/mit6_00scs11_lec21)
> *   [Lecture code (PY)]({{< baseurl >}}/resources/lec21)
> *   [Lecture slides (![This resource may not render correctly in a screen reader.](/images/inacessible.gif)PDF)]({{< baseurl >}}/resources/mit6_00scs11_lec21_slides)

Check Yourself
--------------

What are filters used for?

{{< div-with-class "reveal1">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle1">}}

Filters allow us to choose which features to use for our classification, so that we are basing our inferences on the most relevant information (e.g. teeth instead of body size for dietary habits of mammals).

{{< /div-with-class >}}

What is a graph?

{{< div-with-class "reveal2">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle2">}}

A set of objects called nodes (or vertices) connected by a set of edges (or arcs).

{{< /div-with-class >}}

What is a digraph?

{{< div-with-class "reveal3">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle3">}}

A graph with unidirectional edges.

{{< /div-with-class >}}

What is a weighted graph?

{{< div-with-class "reveal4">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle4">}}

A graph in which each edge has an associated weight.

{{< /div-with-class >}}

Based on the code in the handout, why is Graph a subclass of Digraph, rather than the other way around?

{{< div-with-class "reveal5">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle5">}}

Edge has a source and destination, and is therefore unidirectional already. This makes it easier for us to treat the bidirectional case Graph (where there is an edge for each direction) as a special case of Digraph.

{{< /div-with-class >}}

« [Previous]({{< baseurl >}}/pages/unit-3/lecture-20-more-clustering) | [Next]({{< baseurl >}}/pages/unit-3/lecture-22-using-graphs-to-model-problems-part-2) »