---
title: " render phase and commit phase"
date: 2025-05-11
categories: [Blog]
tags: [GitHub, React]
---

Here are the key points:

* [When a component's props or state change, React runs the components related to the changed part and virtually calculates what the new UI should look like.]
* [Render Phase: The phase where we decide and plan how to update the UI.]
* [Commit Phase: The phase where the planned changes are reflected on the actual screen (DOM) and additional tasks are processed.]
* [React uses an abstraction layer called the virtual DOM to manage efficient UI updates.]
* [React's Render Phase has the characteristics of no guaranteed order and can be interrupted.]

What I felt:
[Once we make a plan, we have to implement it.]