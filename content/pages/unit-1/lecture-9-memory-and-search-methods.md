---
content_type: page
parent_title: Unit 1
parent_uid: 975ad7bf-dd9c-4ffe-26b6-710fa718d5e6
title: Memory and Search Methods
uid: 518bf74e-c414-e8ec-f4d5-55616396f6d0
---

« [Previous]({{< baseurl >}}/pages/unit-1/lecture-8-efficiency-and-order-of-growth) | [Next]({{< baseurl >}}/pages/unit-1/quiz-i) »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
![Graphic representation of sorting a list for efficient search.]({{< resource_file cd3922cc-1926-8e6a-89d0-4cd94670fbaa >}})
{{< tdclose >}}
{{< tdopen >}}


This lecture discusses how indirection is used to provide an efficient implementation of Python lists and other data structures. It also presents and analyzes the efficiency of selection and merge sort.


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Activities
------------------

### Lecture Videos

*   [Lecture 9: Memory and Search Methods]({{< baseurl >}}/resources/lecture-9-memory-and-search-methods)

> ### About this Video
> 
> Topics covered: Memory, storage, indirection, sorting.
> 
> ### Resources
> 
> *   [Lecture code handout (PDF)]({{< baseurl >}}/resources/mit6_00scs11_lec09)
> *   [Lecture code (PY)]({{< baseurl >}}/resources/lec09)

Check Yourself
--------------

What is indirection (in computing)?

{{< div-with-class "reveal1">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle1">}}

Indirection is the ability to access something using a name or reference instead of the value itself.

{{< /div-with-class >}}

We know that a linear search works on all lists and is O(len(L)). Can we sort a list in sub-linear time?

{{< div-with-class "reveal2">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle2">}}

No, because we can't sort a list without looking at each element at least once.

{{< /div-with-class >}}

Can we even do it in linear time?

{{< div-with-class "reveal3">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle3">}}

The answer is probably, no. But we can do it in O(n log n), where n is the length of the list.

{{< /div-with-class >}}

Further Study
-------------

These optional resources are provided for students that wish to explore this topic more fully.

### Readings

*   [8.7. Sets—Unordered collections of unique elements](https://web.archive.org/web/20120410204204/http://docs.python.org/library/sets.html). Python Standard Library.

### Related Lectures

*   [_6.01SC Introduction to Electrical Engineering and Computer Science I_](/courses/6-01sc-introduction-to-electrical-engineering-and-computer-science-i-spring-2011/pages/index.htm).
    *   [Search Algorithms](/courses/6-01sc-introduction-to-electrical-engineering-and-computer-science-i-spring-2011/pages/unit-4-probability-and-planning/search-algorithms)
    *   [Optimizing a search](/courses/6-01sc-introduction-to-electrical-engineering-and-computer-science-i-spring-2011/pages/unit-4-probability-and-planning/optimizing-a-search)
*   [_6.006 Introduction to Algorithms_](/courses/6-006-introduction-to-algorithms-spring-2008/). 6.006 lectures assume a greater level of mathematical sophistication than does 6.00SC. Read the lecture notes on:
    *   Binary search trees
    *   Sorting
    *   Searching

« [Previous]({{< baseurl >}}/pages/unit-1/lecture-8-efficiency-and-order-of-growth) | [Next]({{< baseurl >}}/pages/unit-1/quiz-i) »