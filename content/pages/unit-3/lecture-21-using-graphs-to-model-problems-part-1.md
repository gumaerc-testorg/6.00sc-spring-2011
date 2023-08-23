---
content_type: page
description: This section contains a lecture video and resources, and lecture questions.
draft: true
learning_resource_types: []
ocw_type: CourseSection
parent_title: Unit 3
parent_type: CourseSection
parent_uid: 82c15099-81b2-70b9-823b-c741f08c9b32
title: Using Graphs to Model Problems, Part 1
uid: e1b5ff21-127d-fb30-33e3-98fce88c42e6
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---
« {{% resource_link fc440c95-aa3e-3ffa-8cff-14461dc75eee "Previous" %}} | {{% resource_link d4f15989-167b-6654-ef5c-a2931d758afd "Next" %}} »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
{{< resource 60ac9bba-264e-4869-5fd6-4a52189ef432 >}}
{{< tdclose >}}
{{< tdopen >}}


This lecture begins by finishing up k-means clustering. It then moves on to introduce the notion of modeling things using graphs (sets of nodes and edges that link them).


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Activities
------------------

### Lecture Videos

*   {{% resource_link fb62179f-6316-19bb-2694-4725975e3042 "Lecture 21: Using Graphs to Model Problems, Part 1" %}}

> ### About this Video
> 
> Topics covered: Pseudocode, graphs, nodes, edges, adjacency matrix, adjacency list.
> 
> ### Resources
> 
> *   {{% resource_link 0ceac7c1-7f78-3549-ea4a-e2eec5f0112b "Lecture code handout (PDF)" %}}
> *   {{% resource_link 78807f07-6347-27bc-6c50-0f3a475542c7 "Lecture code (PY)" %}}
> *   {{% resource_link "03b3f2e0-3d53-422b-5100-b4f06b577dde" "Lecture slides (PDF)" %}}

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

« {{% resource_link fc440c95-aa3e-3ffa-8cff-14461dc75eee "Previous" %}} | {{% resource_link d4f15989-167b-6654-ef5c-a2931d758afd "Next" %}} »