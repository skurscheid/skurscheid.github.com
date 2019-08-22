---
layout: post
title: "interactive GPU queue on raijin"
description: ""
category: CLI, raijin
tags: []
---

~~~~
qsub -I -P kv78 -q gpu -l mem=16GB -l ngpus=2 -l ncpus=6
~~~~

{% include JB/setup %}
