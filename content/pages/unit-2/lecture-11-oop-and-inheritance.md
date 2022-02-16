---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: Unit 2
parent_type: CourseSection
parent_uid: ddc5db7a-5c64-e3bd-a565-b36f4ed76287
title: OOP and Inheritance
uid: c7f4e874-e827-c2ec-07cb-6c920e3e1ee3
---

« [Previous]({{< baseurl >}}/pages/unit-2/lecture-10-hashing-and-classes) | [Next]({{< baseurl >}}/pages/unit-2/lecture-12-introduction-to-simulation-and-random-walks) »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
![Photograph of ink droplets mixing in water.]({{< resource_file c482305b-06dc-39b2-b789-d387bd1245a0 >}})
{{< tdclose >}}
{{< tdopen >}}


In this lecture, we learn about object-oriented programming (OOP) and how classes are used to implement new types of objects in Python. As part of that discussion we introduce inheritance.

_Image courtesy of The Ridg on Flickr._


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Activities
------------------

### Lecture Videos

*   [Lecture 11: OOP and Inheritance]({{< baseurl >}}/resources/lecture-11-oop-and-inheritance)

> ### About this Video
> 
> Topics covered: Object-oriented programming (OOP), abstract data types, specifications, subclasses, inheritance.
> 
> ### Resources
> 
> *   [Lecture code handout (PDF)]({{< baseurl >}}/resources/mit6_00scs11_lec11)
> *   [Lecture code (PY)]({{< baseurl >}}/resources/lec11)

### Recitation Videos

*   [Recitation 5: Quiz 1 Answers and Object-Oriented Programming]({{< baseurl >}}/resources/recitation-5-quiz-1-answers-and-object-oriented-programming)

> ### About this Video
> 
> Topics covered: Double recursion, big O notation, binary function, run times, object-oriented programming, classes, encapsulation, methods, class hierarchy, subclasses, inheritance, polymorphism, accessor and mutator functions, Person example, underbar methods, self parameter.

Check Yourself
--------------

What is an instance?

{{< div-with-class "reveal1">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle1">}}

Instances are the actual objects built in accordance with the qualities of the class.

{{< /div-with-class >}}

What is an abstract data type?

{{< div-with-class "reveal2">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle2">}}

A set of objects and the operations on those objects.

{{< /div-with-class >}}

What is encapsulation?

{{< div-with-class "reveal3">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle3">}}

Encapsulation means that names (of variables and methods) are stored in locations that then have to be accessed, called namespaces.

{{< /div-with-class >}}

What is data hiding?

{{< div-with-class "reveal4">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle4">}}

Data hiding makes data invisible to users of the object, requiring it to be accessed only via the object's methods.

{{< /div-with-class >}}

What functions can subclasses use?

{{< div-with-class "reveal5">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle5">}}

Subclasses can use all the functions of their superclass. They can also use any functions that are defined within the subclass; however, if the subclass uses the same name for a function which has also been used in the superclass, it will only use the subclass definition of that function.

{{< /div-with-class >}}

« [Previous]({{< baseurl >}}/pages/unit-2/lecture-10-hashing-and-classes) | [Next]({{< baseurl >}}/pages/unit-2/lecture-12-introduction-to-simulation-and-random-walks) »