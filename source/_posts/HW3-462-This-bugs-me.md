---
title: 'This bugs me'
date: 2021-02-04 08:00:00
tags: CSCI462
---

## 6.4

**Find the Oldest Bug**

One of the oldest open bugs in the Zulip project is [Issue #387](https://github.com/zulip/zulip/issues/387).


## 6.5

**Create Your Bug Tracker Account**

Zulip uses the GitHub issues feature for bug tracking, so no need to create an account elsewhere, although I have joined their developer chat Zulip server.

## 6.6

**Reproduce a Bug**

The other day while exploring the Zulip project my team and I ran into a lot of issues related to how Zulip handles the deletion/deactivation of stream (similar to channels on Slack).
A bug I was able to reproduce involved users that were part of a stream that has since been deactivated are still able to find the stream in the search functionality and then edit their old messages in the stream.

Steps to Reproduce:

1. Create a stream and comment in it

2. Deactivate the stream

3. Search for the stream using the query "stream:name"

4. Edit an old comment in the deactivated stream

## 6.7

**Bug Triage**

## References

- [Teaching Open Source: Debugging_the_Code](https://quaid.fedorapeople.org/TOS/Practical_Open_Source_Software_Exploration/html/ch-Debugging_the_Code.html)
