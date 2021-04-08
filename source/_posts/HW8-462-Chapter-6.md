---
title: "Chapter 6"
date: 2021-03-25 08:00:00
tags: CSCI462
---

## Reflections

Chapter 6 of Client Centered Software Development, Database Development, covers the COFOSS approach to designing, implementing, testing, and maintaining databases for use in software projects.
Last semester I took CofC's Database Concepts class, so I found this chapter quite interesting, especially due to its focus upon the practical aspects of integrating databases with software projects, which we only skimmed over in that course.

I found section 6.2, Database Access, to be particularly interesting due to its focus on connecting a program to a database as well as database security.
While in Database Concepts we focused upon designing, normalizing, and manipulating databases this section went a step further and discussed how databases are utilized in a variety of programming languages including Python, PHP, and Ruby. This is especially relevant as while working on Zulip my team and I have had to learn how to interact with Zulip's database using python.

Additionally, security considerations are extremely important to consider when using databases, as sensitive data can be exposed and/or tampered with if databases are used/configured improperly.
For instance, improper input sanitation can lead to vulnerabilities like SQL injection, where an adversary gains the ability to execute SQL commands on an application's underlying database.

![SQL Injection Comic](https://imgs.xkcd.com/comics/exploits_of_a_mom.png )

Overall I found this chapter to be pretty interesting and quite relevant to the work we are doing for this course. I have always felt that database design is an under-discussed topic in software engineering, so I was glad to see it included here and learn a bit more about it. 

## References

- Client Centered Software Development: The COFOSS Approach
