---
title: 'HW3: Chapters 11 & 12'
date: 2020-09-03 04:00:00
tags: CSCI362
---

## 11.4

**What is the common characteristic of all architectural styles that are geared to supporting software fault tolerance?**

---

At their core, all architectures for supporting software fault tolerance should be redundant.

They should be specific, verify correctness, and handle all possible faults.

## 11.7

**It has been suggested that the control software for a radiation therapy machine, used to treat patients with cancer, should be implemented using N-version programming. Comment on whether or not you think this is a good suggestion.**

---

Control software for highly critical systems such as radiation therapy machines are an excellent use case for N-version programming. In systems like these a single mistake can have severe consequences as demonstrated by the Therac-25 accidents, and N-version programming drastically reduces the likelihood of an uncaught software or hardware fault.

## 11.9

**Explain why you should explicitly handle all exceptions in a system that is intended to have a high level of availability.**

---

Uncaught exceptions cause system failures and downtime, so whenever possible an exception should be handled by a program to allow a system to recover from an exception on its own and significantly improve fault tolerance.

## 12.5

**A train protection system automatically applies the brakes of a train if the speed limit for a segment of track is exceeded, or if the train enters a track segment that is currently signaled with a red light (i.e., the segment should not be entered). There are two critical-safety requirements for this train protection system:**
1. **The train shall not enter a segment of track that is signaled with a red light.**
2. **The train shall not exceed the specified speed limit for a section of track.**
**Assuming that the signal status and the speed limit for the track segment are transmitted to on-board software on the train before it enters the track segment, propose five possible functional system requirements for the onboard software that may be generated from the system safety requirements.**

---

1. The system should be able to determine what speed it is traveling, and what the speed limit for the current section is.
2. The system should be able to identify whether or not the next segment has a red signal light.
3. The system should be able to apply brakes when the speed is too high or the upcoming track has a red signal.
4. The system should be able to disable the brakes when there is no longer a red signal, and the speed is below the limit.
5. The system should be able aware of hardware/software faults and inform the operator if there are any issues.

## References
- [An Investigation of the Therac-25 Accidents](http://bowringj.people.cofc.edu/docs/therac-25.pdf)
