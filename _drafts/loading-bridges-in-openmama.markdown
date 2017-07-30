---
layout: post
title:  "Loading Bridges in OpenMAMA"
date:   2017-07-30 12:00:00 +0100
categories: openmama bridges
---

# Introduction

OpenMAMA is the Middleware Agnostic Messaging API. It's designed to provide an abstraction layer over commonly used message oriented middlewares in the financial sector - middlewares which are used to distribute hundreds of thousands of messages to potentially thousands of clients across a broad spectrum of usecases.

OpenMAMA's abstraction is based around the concept of 'bridges' - effectively small libraries which provide a mapping between OpenMAMA's concepts and the underlying middleware.
