---
title: "Hoisting"
date: 2025-05-20
categories: [Blog]
tags: [GitHub, JS]
---

Here are the key points:

* [Hoisting: In JavaScript code, it behaves as if variable or function declarations are hoisted to the top of the code.]
* [Variables declared with var are hoisted, so they tell you at the top of the code, "I have this variable!", but actually assigning a value to that variable (assignment) is executed at the original location -> so if you try to use a var variable before assigning a value to it, you get undefined (no value yet!)]
* [let and const variables will cause an error (ReferenceError) if you try to use them until a value is assigned to them.]

What I felt:
[Why use it before allocation?]