---
content_type: page
parent_title: Unit 1
parent_uid: 975ad7bf-dd9c-4ffe-26b6-710fa718d5e6
title: Efficiency and Order of Growth
uid: 51a3082b-b50b-dc70-f44f-e076ffa558d6
---

« [Previous]({{< baseurl >}}/pages/unit-1/lecture-7-debugging) | [Next]({{< baseurl >}}/pages/unit-1/lecture-9-memory-and-search-methods) »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
![Graph showing various logarithmic curves.]({{< resource_file 909d2baa-718a-f8cd-3fd3-18c827218766 >}})
{{< tdclose >}}
{{< tdopen >}}


This lecture revolves around the topic of algorithmic efficiency. It introduces the random access model (RAM) of computation and "big O notation" as a way to talk about order of growth. It concludes with binary search.


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Activities
------------------

### Lecture Videos

*   [Lecture 8: Efficiency and Order of Growth]({{< baseurl >}}/resources/lecture-8-efficiency-and-order-of-growth)

> ### About this Video
> 
> Topics covered: Efficiency, problem reduction, RAM, best case, worst case, expected case, growth, exponential growth, polynomial growth, logarithmic growth, global variables.
> 
> ### Resources
> 
> *   [Lecture code handout (PDF)]({{< baseurl >}}/resources/mit6_00scs11_lec08)
> *   [Lecture code (PY)]({{< baseurl >}}/resources/lec08)
> *   [showGrowth code (PY)]({{< baseurl >}}/resources/showgrowth)

### Recitation Videos

*   [Optional Recitation: Algorithm Complexity and Class Review]({{< baseurl >}}/resources/optional-recitation-algorithm-complexity-and-class-review)

> ### About this Video
> 
> Topics covered: Big O notation, algorithm complexity, algorithm comparison example, object-oriented programming, Person class example, defensive programming, private attributes, mutability, aliasing.
> 
> ### Resources
> 
> *   [Recitation handout (PDF)]({{< baseurl >}}/resources/mit6_00scs11_rec04) (Courtesy of Sarina Canelake. Used with permission.)

Check Yourself
--------------

Why is efficiency important?

{{< div-with-class "reveal1">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle1">}}

Efficiency determines how long our programs take to run; when large sets of data are being handled, it can make a huge difference (on the order of years or even millennia) whether our program is efficient or not.

{{< /div-with-class >}}

What notation do we use to state complexity?

{{< div-with-class "reveal2">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle2">}}

Big O notation.

{{< /div-with-class >}}

« [Previous]({{< baseurl >}}/pages/unit-1/lecture-7-debugging) | [Next]({{< baseurl >}}/pages/unit-1/lecture-9-memory-and-search-methods) »