---
layout: post
title:  "Custom Memory Allocators in OpenMAMA"
date:   2017-07-30 12:00:00 +0100
categories: openmama memory
---

# Introduction

One of the interesting factors in high performance code is the use of custom memory allocators to handle the allocation and freeing of memory in a highly optimised fashion. This post explores some of the potential mechanisms via which such an allocator can be used in an OpenMAMA application, and the performance gains we can expect to discover in using one. 
