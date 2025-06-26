---
title: "Event Loop?"
date: 2025-04-28
categories: [Blog]
tags: [GitHub, event loop]
---

Here are the key points:

* [The event loop allows JavaScript to handle multiple tasks without stopping the UI from updating.]
* [Execution order:
Execute synchronous code on the call stack
Complete the current macrotask
Execute all tasks in the microtask queue in order
When the call stack is empty, the event loop takes the next task from the macrotask queue and sends it to the call stack
This process is repeated]

What I felt:
[I keep forgetting that API stands for Application Program Interface, a set of functions for developing applications.]