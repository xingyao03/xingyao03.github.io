---
layout: project
type: project
image: img/cotton/cotton-square.png
title: "AuthoringAssistant"
date: 2023-08-05
labels:
  - Java
summary: "A lab done in ICS 211 which examines user input."
---

<img class="img-fluid" src="../img/cotton/cotton-header.png">

In this lab program, the user input is taken in first and then a menu is printed with options to analyze and edit the input. In this lab I learned a lot of other methods that were really helpful tools such as "replaceAll" and "toLowerCase()." 


Below is the part that shows finding the number of times a character is found:

```Java
public static int findText(String findText, String userText) {
      userText = userText.toLowerCase();
      String[] words = userText.split(" ");
      int count = 0;

      for (int i = 0; i < words.length; i++) {
            if (words[i].equals(findText)) {
               count++;
               }
            }
         return count;
      }
``
