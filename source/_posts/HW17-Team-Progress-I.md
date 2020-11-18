---
title: 'HW17: Team Progress I'
date: 2020-11-05 04:00:00
tags: CSCI362
---

At this point in time my team and I have been working on and thinking about our term project for quite some time, and we are pretty pleased with our progress so far.

We have designed and implemented a significant portion of our testing framework and currently have it in a working state, although we plan to clean it up considerably (especially the output). Additionally we have written 2/5 test case drivers and 10/25 test cases for our framework. Overall we feel pretty confident with our design and plan on getting a lot more work done in the coming weeks.

Although we are happy with our progress there are some challenges we encountered along the way, and at least one more we see on the horizon. These issues all stem from the sheer scale of the open source project we chose to develop our framework for, Moodle. Due to the nature of the Moodle project, much of the code requires a database and a configuration in order to run, which makes our work a bit more difficult as we are trying to make our framework as portable as possible. We have two option in moving forward with this constraint, automating the Moodle install process or avoiding tests which require the database. Currently we are leaning towards avoiding this type of test as we have had no shortage of Moodle components to test that do not require the DB and we are viewing an automated install as an "extra" thing we could do to demonstrate the versatility of our framework if time allows after we have completed the basic project requirements.

As I stated above, I am currently pretty happy with my teams progress and we are hoping our project continues to develop at the current pace.
