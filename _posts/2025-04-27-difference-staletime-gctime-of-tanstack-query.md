---
title: "stale time and gc time"
date: 2025-04-26
categories: [Blog]
tags: [GitHub, stale time, gc time]
---

Here are the key points:

* [stale time: When data is first fetched from a web server, during this time, even if a new request comes, the server will not be asked again and the data already fetched will be displayed as is - the default value is 0 seconds.]
* [gc time: When a web page no longer uses a piece of data, it keeps it in memory for the gcTime period in case it can be used again, but if no one looks for it after the gcTime period has elapsed, it is completely removed from the cache to free up memory space - the default is 5 minutes.]
* [Importance: Prevents memory leaks, improves program efficiency]

What I felt:
[My memory is leaking.]