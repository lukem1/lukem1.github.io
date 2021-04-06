---
title: "What's Happening?"
date: 2021-02-11 08:00:00
tags: CSCI462
---

## Reflections

For today's post I read an article in IEEE Software titled "**Serverless Computing-Where Are We Now, and Where Are We Heading?**".
The article discusses the state of so-called serverless computing and some of the implications of its rise in popularity.

In my opinion the term serverless computing is somewhat misleading, but the article poses a definition which demonstrates the term fits quite well:

**"[serverless computing] can be considered 'serverless,' not because servers aren’t running, but because developers do not need to think about them anymore."**

I found the most interesting portion of the article to be a section discussing the benefits and issues of serverless systems.

Firstly, the mentioned benefits included the cost and time savings in serverless architecture from the operations perspective.
Serverless computing cuts out the need for huge amounts of server, network, and other infrastructure, which not only has its own cost savings, but simplifies much more of the software engineering process.
A scenario that I have found particularly interesting is one where a web application faces large shifts in demand. Without a serverless architecture scaling takes time and can be very costly, but with serverless computing you can scale your application dynamically and pay only for the server computing you need at any instance in time.

Finally, one of the difficulties raised by serverless computing that I found interesting was the danger of vendor lock in. Serverless architecture often requires designs specific to a cloud platform, and I think it is important to consider how this can cause an over reliance upon a third party, and make an application vulnerable to changes by the cloud provider, such as price hikes or discontinuation.

Overall I found this article to be quite interesting and insightful. And I feel that serverless computing will continue to grow and evolve over the coming years.

## References

- [Serverless Computing-Where Are We Now, and Where Are We Heading?](https://doi.ieeecomputersociety.org/10.1109/MS.2020.3028708)
