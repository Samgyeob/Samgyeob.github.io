---
title: "Browser Rendering Pipeline?"
date: 2025-05-03
categories: [Blog]
tags: [GitHub, browser rendering pipeline]
---

Here are the key points:

* [HTML Parsing: The browser converts HTML text into a DOM (Document Object Model) tree
CSS Parsing: The browser converts CSS text into a CSSOM (CSS Object Model) tree]
* [Create a render tree: Combine the DOM tree and CSSOM tree to create a render tree consisting of elements and style information to be displayed on the screen. Layout: Calculate the size and position of each element in the render tree (reflow may occur)]
* [Paint: Paint each element on the screen based on the calculated layout (possibly repainting)
Composite: Composite multiple drawn layers to finally display them on the screen]

What I felt:
[Still I can't understand.]