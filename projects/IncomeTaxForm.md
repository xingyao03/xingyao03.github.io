---
layout: project
type: project
image: img/AC08002C-76DA-475C-A2F8-62DFFD27D3EE_1_201_a.jpeg
title: "IncomeTaxForm"
date: 2023-08-02
labels:
  - Java
<img width="200px" class="rounded float-start pe-4" src="../img/22F2BB4A-1720-4943-8042-A404A8A8C691.jpeg">

summary: "This is a mini program made in my ICS 211 lab calculating the tax depending on status of the input information."
---

This program takes in user input to calculates U.S. income tax owned given wages, taxable interests, umemployment compensation, status, and taxes withheld. Within the program, there are multiple functions each completing a different task and building ontop of another.

I took full responsibility of the project and from this project I learned how to format my string when there are numbers involved. I learned to use methods from the Math class such as MATh.abs() which returns an absolute value of the input. I also learned to choose the right declaration of varaible when there are decimal points invovled, such as using double instead of integer.


Below is part of the code that calculates the adjusted gross income:

```Java
   public static int calcAGI(int wages, int interest, int unemployment) {
      int AGI = Math.abs(wages) + Math.abs(interest) + Math.abs(unemployment);
      return AGI;
   }
```
