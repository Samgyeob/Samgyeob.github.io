---
title: "async and defer"
date: 2025-05-21
categories: [Blog]
tags: [GitHub, script tag, JS]
---

Here are the key points:

* [async:
The script will be executed immediately after it is downloaded.
There will be a brief pause in HTML parsing when the script is executed.
If there are multiple async scripts, they will be executed in order as they are downloaded.
Suitable for scripts that can be executed independently (e.g. Google Analytics).]
* [defer:
Run after HTML parsing is complete: Runs after the HTML document has been completely parsed.
Runs just before the DOMContentLoaded event occurs.
If there are multiple defer scripts, they will be executed in the order in which they were written in the HTML.
Suitable for scripts where execution order is important or that contain main application logic.]

What I felt:
[What does it mean that understanding these differences and using them appropriately can greatly improve the loading performance of your web pages?]