---
content_type: page
description: This section contains a lecture video and resources, lecture questions,
  and further study resources.
draft: true
learning_resource_types: []
ocw_type: CourseSection
parent_title: Unit 1
parent_type: CourseSection
parent_uid: 975ad7bf-dd9c-4ffe-26b6-710fa718d5e6
title: Memory and Search Methods
uid: 518bf74e-c414-e8ec-f4d5-55616396f6d0
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---
« {{% resource_link 51a3082b-b50b-dc70-f44f-e076ffa558d6 "Previous" %}} | {{% resource_link f47a2aad-b696-870f-d73f-2911223c7ebf "Next" %}} »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
{{< resource cd3922cc-1926-8e6a-89d0-4cd94670fbaa >}}
{{< tdclose >}}
{{< tdopen >}}


This lecture discusses how indirection is used to provide an efficient implementation of Python lists and other data structures. It also presents and analyzes the efficiency of selection and merge sort.


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Activities
------------------

### Lecture Videos

*   {{% resource_link dca6b717-432f-b720-570a-9b6eca26dbf5 "Lecture 9: Memory and Search Methods" %}}

> ### About this Video
> 
> Topics covered: Memory, storage, indirection, sorting.
> 
> ### Resources
> 
> *   {{% resource_link 18f23403-c7c5-e742-a0bf-9886b859f300 "Lecture code handout (PDF)" %}}
> *   {{% resource_link 022119d5-7a47-311f-4715-07f58666d667 "Lecture code (PY)" %}}

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

*   {{% resource_link "4692fb18-778a-4296-beab-38dffd791497" "8.7. Sets—Unordered collections of unique elements" %}}. Python Standard Library.

### Related Lectures

*   [_6.01SC Introduction to Electrical Engineering and Computer Science I_](/courses/6-01sc-introduction-to-electrical-engineering-and-computer-science-i-spring-2011).
    *   [Search Algorithms](/courses/6-01sc-introduction-to-electrical-engineering-and-computer-science-i-spring-2011/pages/unit-4-probability-and-planning/search-algorithms)
    *   [Optimizing a search](/courses/6-01sc-introduction-to-electrical-engineering-and-computer-science-i-spring-2011/pages/unit-4-probability-and-planning/optimizing-a-search)
*   [_6.006 Introduction to Algorithms_](/courses/6-006-introduction-to-algorithms-spring-2008). 6.006 lectures assume a greater level of mathematical sophistication than does 6.00SC. Read the lecture notes on:
    *   Binary search trees
    *   Sorting
    *   Searching

« {{% resource_link 51a3082b-b50b-dc70-f44f-e076ffa558d6 "Previous" %}} | {{% resource_link f47a2aad-b696-870f-d73f-2911223c7ebf "Next" %}} »