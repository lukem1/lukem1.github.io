---
title: 'HW18: Chapter 21 and Chapter 22'
date: 2020-11-10 04:00:00
tags: CSCI362
---
## 21.4
**What are the commonly used architectural patterns in real-time systems and when are they used?**

#### Observe and React

This architecture involves using data from sensors to provide information about an environment as well as detect when certain events occur in order to initiate a response. This pattern is often used when a system is designed to work with a human operator and provide them with information. For example, a security system that sets of an alarm when a break in is detected, or an industrial control system which alerts an operator when something is going wrong and shuts down machinery.

#### Environmental Control

This architecture involves using data from sensors to detect to changes in an environment and using actuators to manipulate that environment in response. It is used in systems where direct interactions with the environment are desired, for example, the text describes an anti skid braking system which can detect when wheels begin skidding and adjust the brakes to minimize risk.

#### Process Pipeline

This architecture involves transforming data from one representation to another before processing to allow for more efficient data processing. It is often used when sensors collect large amounts of data from the environment and it is either not possible or not necessary to process the data in real time.

## 22.6
**Fixed-price contracts, where the contractor bids a fixed price to complete a system development, may be used to move project risk from client to contractor. If anything goes wrong, the contractor has to pay. Suggest how the use of such contracts may increase the likelihood that product risks will arise.**

As has been long established throughout this blog and this course, software projects tend to evolve throughout the software engineering process through means of schedule slippage, requirements changes, or a myriad of other issues which require flexibility. Fixed-price contracts simply do not provide the room for the flexibility that software projects often require, and this can cause issues to be ignored by contractors in order to meet contracts by any means, and this can be a vicious cycle as projects continue and more and more issues are potentially ignored.
