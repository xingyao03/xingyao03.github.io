---
layout: project
type: project
image: img/E21AD2C3-14C7-43EE-9343-4E5B4D044E72_1_201_a.jpeg
title: "SelfPayKiosk"
date: 2023-08-10
published: true
labels:
  - Java
summary: "A self pay kiosk program created in ICS 211."
---

<img width="200px" class="rounded float-start pe-4" src="../img/5D80B866-6763-4ACB-BA90-6A1E03CD4887_4_5005_c.jpeg">

# **Summary of Project**
A self pay kiosk program created in ICS 211. The program is designed to support basic operations such as scan item, cancel transaction, checkout, make payment and etc. 

# **Role & What I learned**
I took full responsibility and worked indepedently on this project. In this program, it is the first time I experimented with the main class separated from the SelfPayKiosk class. I learned a lot on the way trying to make sense of how the different classes worked on their own and puting everything together. I learned to use the keyword "final" when I want the varaible to be fixed and not changeable. With two seperate classes the code is much more readable and organized.


**Below is a part of the code that shows applying payment to amount due:**

```Java
public void makePayment(double payment) {
      if (checkedOut) {
         if (payment >= amountDue) {
            totalSales += amountDue;
            numCustomers++;
            amountDue = 0.0;
            checkedOut = false;
            }
         else if (payment >= 0) {
            totalSales += payment;
            amountDue -= payment;
            }
         }
   }
```
