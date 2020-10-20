---
title: 'HW12: Chapter 16'
date: 2020-10-15 04:00:00
tags: CSCI362
---
## 16.9
**Design the interfaces of components that might be used in a system for an emergency control room. You should design interfaces for a call-logging component that records calls made, and a vehicle discovery component that, given a post code (zip code) and an incident type, finds the nearest suitable vehicle to be dispatched to the incident.**

Call Logging Component Interface

Requires
- dispatch(zip, type)

Provides
- logCall(call)
- determineLocation(call)
- listUnresolved()
- resolveCall(call)

Vehicle Discovery Component Interface

Requires
- resolveCall()

Provides
- dispatch(zip, type)
- filterResponders(type)
- locateResponders(zip)
