---
layout: post
title:  "Testing OpenMAMA with Googles Sanitizers"
date:   2017-07-30 12:00:00 +0100
categories: openmama sanitizers llvm
---

# Introduction

Most engineers who spend any length of time C ultimately find themselves getting intimately aquianted with the Valgrind toolset. For the unitiated, Valgrind is a memory analyzer and profiler which runs an application in something like a virtual machine, and is used to check for a wide assortment of memory issues that are inherent in any C project. It also has a range of plugins that allow it to check for other problematic behaviour, including the 'helgrind' framework for multi-threaded code.

One of the interesting developments in C and C++ over recent years has come in Google's ['Sanitizers'][Google Sanitizers] project.

[Google Sanitizers]: https://github.com/Google/Sanitizers
