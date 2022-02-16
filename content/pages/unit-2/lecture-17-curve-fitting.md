---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
parent_title: Unit 2
parent_type: CourseSection
parent_uid: ddc5db7a-5c64-e3bd-a565-b36f4ed76287
title: Curve Fitting
uid: e632ebd5-0e8f-47bb-2666-d9152f62e9e4
---

« [Previous]({{< baseurl >}}/pages/unit-2/lecture-16-using-randomness-to-solve-non-random-problems) | [Next]({{< baseurl >}}/pages/unit-2/lecture-18-optimization-problems-and-algorithms) »

Session Overview
----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
![Diagram of spring under tension.]({{< resource_file 7de06a38-4626-eee8-6497-de9a3295e785 >}})
{{< tdclose >}}
{{< tdopen >}}


This lecture is about how to use computation to help understand experimental data. It talks about using linear regression to fit a curve to data, and introduces the coefficient of determination as a measure of the tightness of a fit.


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Session Activities
------------------

### Lecture Videos

*   [Lecture 17: Curve Fitting]({{< baseurl >}}/resources/lecture-17-curve-fitting)

> ### About this Video
> 
> Topics covered: Arrays, curve fitting, numpy, pylab, least squares fit, prediction.
> 
> ### Resources
> 
> *   [Lecture code handout (PDF)]({{< baseurl >}}/resources/mit6_00scs11_lec17)
> *   [Lecture code (PY)]({{< baseurl >}}/resources/lec17)
> *   [Lecture slides (PDF)]({{< baseurl >}}/resources/mit6_00scs11_lec17_slides)
> *   [Lecture data files (ZIP)]({{< baseurl >}}/resources/lec17_data) (This ZIP file contains: 3 .txt files.)

### Recitation Videos

*   [Recitation 7: Distributions, Monte Carlo, and Regressions]({{< baseurl >}}/resources/recitation-7-distributions-monte-carlo-and-regressions)

> ### About this Video
> 
> Topics covered: Data distributions, mean, standard deviation, Monte Carlo simulations, Monty Hall problem, Riemann sum method, data regressions, r^2 (r-squared), coefficient of termination, scientific applications of programming.

Check Yourself
--------------

What is an objective function?

{{< div-with-class "reveal1">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle1">}}

One that provides a quantitative assessment of how well the curve fits the data.

{{< /div-with-class >}}

What method of curve fitting is used by polyfit?

{{< div-with-class "reveal2">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle2">}}

Linear regression.

{{< /div-with-class >}}

What does curve fitting do?

{{< div-with-class "reveal3">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle3">}}

Relates an independent variable to an estimated value of a dependent variable.

{{< /div-with-class >}}

What is the coefficient of determination?

{{< div-with-class "reveal4">}}

› _View/hide answer_

{{< /div-with-class >}}{{< div-with-class "toggle4">}}

Coefficient of determination, R^2, is equal to 1 – (estimated error)/(variance of the actual data)

{{< /div-with-class >}}

« [Previous]({{< baseurl >}}/pages/unit-2/lecture-16-using-randomness-to-solve-non-random-problems) | [Next]({{< baseurl >}}/pages/unit-2/lecture-18-optimization-problems-and-algorithms) »