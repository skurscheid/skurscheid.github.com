---
layout: post
category: R
title: Retrieving host/machine name in R
date: '2016-05-02 12:53'
---

{% include JB/setup %}

A simple way to retrieve the local machine name in R:

```
R> Session.info()["nodename"]
          nodename
"your machine name"
```

(Found at [http://www.walkingrandomly.com/?p=5023])
