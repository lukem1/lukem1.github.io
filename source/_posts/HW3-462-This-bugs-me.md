---
title: 'This bugs me'
date: 2021-02-04 08:00:00
tags: CSCI462
---

This post contains the results of my completion of the following exercises in TOS Chapter 6.

## 6.4

**Find the Oldest Bug**

One of the oldest open bugs in the Zulip project is [Issue #387](https://github.com/zulip/zulip/issues/387). It is an issue with the markdown parser in Zulip which prevents images from being attached to a message in certain circumstances. There are numerous commits which reference this issue, including some relatively recent ones, so it is interesting that the issue has remained open for such a long time.


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

[1. Issue 17145](https://github.com/zulip/zulip/issues/17145)

- This issue was related to the Zulip desktop app, which is hosted in a separate repository, so I suggested that the author move it to the proper location.

[2. Issue 17202](https://github.com/zulip/zulip/issues/17202)

- This issue is one our team opened relating to the topic of deactivated steams. I contributed another detail I noticed to the discussion then ended up opening my own issue.

## Conclusions

I found the exercises in this chapter to be very beneficial in getting to know the Zulip open source project and becoming more familiar with it's history and protocols. During the bug triage exercises my team and I also started to plan our first contributions and open our own issues for bugs we have noticed. Overall I found this chapter to be very valuable.

## References

- [Teaching Open Source: Debugging_the_Code](https://quaid.fedorapeople.org/TOS/Practical_Open_Source_Software_Exploration/html/ch-Debugging_the_Code.html)
