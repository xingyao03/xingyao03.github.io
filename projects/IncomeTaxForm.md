---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "IncomeTaxForm"
date: 2023-08-02
labels:
  - Java
summary: "This is a mini program made in my ICS 211 lab calculating the tax depending on status of the input information."
---

This program takes in user input to calculates U.S. income tax owned given wages, taxable interests, umemployment compensation, status, and taxes withheld. Within the program, there are multiple functions each completing a different task and building ontop of another.

Below is part of the code that calculates the adjusted gross income:

```Java
   public static int calcAGI(int wages, int interest, int unemployment) {
      int AGI = Math.abs(wages) + Math.abs(interest) + Math.abs(unemployment);
      return AGI;
   }
```
