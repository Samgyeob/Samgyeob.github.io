---
title: "Event Propagation"
date: 2025-07-23
categories: [Blog]
tags: [GitHub, DOM, event propagation]
---

Here are the key points:

* [Capturing Phase: The event starts at the document (the very top) and travels downwards towards the element where the event actually occurred (the target element). Event listeners configured for capturing will execute during this descent.]
* [Target Phase: The event reaches the target element itself. Any event listeners directly attached to this specific element are executed at this point.]
* [Bubbling Phase: After hitting the target, the event then travels upwards from the target element back to the document. Most events propagate this way by default, and listeners on parent elements will execute during this ascent.]

What I felt:
[What am I learning..?]