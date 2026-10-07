---
layout: page
permalink: /publications/
title: writings 
description: Some of my mathematical writings and slides of talks I've given.
nav: true
nav_order: 1
---

## Theses

{% bibliography --query @*[keywords ^= theses] %}

## Talks

{% bibliography --query @*[keywords ^= talks] %}
