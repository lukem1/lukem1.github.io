---
title: 'HW9: Chapter 8 and Reflections on Testing'
date: 2020-10-01 04:00:00
tags: CSCI362
---

## 8.7
**Write a scenario that could be used to help design tests for the wilderness weather station system.**

A weather station that is part of the wilderness weather station system is damaged when a bear stumbles across it and breaks one of the Instruments. The station recognizes the issue, and reports the fault over the satellite connection. Fred, who is responsible for managing the stations in the region, is notified of the fault by the station maintenance system, and travels to the site to replace the broken instrument. After the instrument is replaced, the system recognizes the new sensor and begins collecting data from the sensor again.

---

## 8.10
**A common approach to system testing is to test the more important functionalities of a system first, followed by the less important functionalities until the testing budget is exhausted. Discuss the ethics involved in identifying what “more important” means.**

When determining which tests are more important to develop on a limited budget, it is extremely important to carefully consider which tests would be most beneficial, and which can be more safely ignored. A developer should clearly first focus upon system critical code and systems, and gradually work towards less critical systems until the budget is depleted.

---

## Reflections on Testing

As has been clearly established throughout this course, it is hard to understate the importance of testing, and the text Software Testing Techniques discusses this in detail.

First, the text begins by analyzing the overarching concepts of testing and defines the goal of testing to be "bug prevention and bug discovery" and poses a the idea of "test before you code", arguing that this mindset can help to prevent bugs before they appear by encouraging software engineers to write tests before they start developing so they can hopefully avoid potential pitfalls. I personally feel that this is an excellent mindset as, like the text describes, a prevented bug is far superior than a corrected bug.

Next the text describes some of the other weapons against bugs, including code inspection, design style, and static analysis. It is clear these weapons are also extremely beneficial to the testing process, as these practices all encourage the development of well designed code. Here the text also describes the pesticide paradox, which describes the situation where the solution to a problem increases the complexity of other problems (i.e. using pesticide to kill one round of bugs increases the prevalence of bugs resistant to that pesticide).  

Finally, the text describes several different methodologies in testing that are important to consider. Including functional vs structural testing and the drawbacks and benefits of separating or integrating design and testing. The latter of these comparisons I find especially interesting, as both cases have clear and relevant benefits/drawbacks, and it is likely often unfeasible to perform both.

Overall, Software Testing Techniques poses several interesting details and conversations, and it is clear that these things are quite important to consider within the realm of testing.

---

## References

These reflections are commentary on the following

- [Software Testing Techniques](http://bowringj.people.cofc.edu/classes/csci%20362/docs/software.testing.introduction.pdf)
