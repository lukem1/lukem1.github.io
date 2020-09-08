---
title: 'HW4: Reflections on Software Failures'
date: 2020-09-08 04:00:00
tags: CSCI362
---

## Reflections

Failures seem inevitable in perhaps all fields, but software engineering seems especially prone to failure, and has seen more than its fair share of incidences from medical disasters to spacecraft accidents. In this post I will be commenting upon some of these software engineering failures as well as discussing some of their underlying causes and the steps that should be taken to avoid these pitfalls while developing software.

The first software failure I will discuss resulted in the Therac-25 accidents. The Therac-25 accidents occurred in the 1980s when a computer radiation therapy machine caused at least six massive overdoses of radiation that resulted in deaths and serious injuries. Investigations into these accidents revealed that poor software engineering practices including “unrealistic” risk assessments and testing, overcomplexity, and lack of documentation and error traceability led to these accidents. The Threac-25 accidents have become a sort of standard model of the dangers of software failures, but unfortunately we still seem to be learning from these mistakes.

More recently, software failures again showed their danger in spacecraft design. “The Role of Software in Spacecraft Accidents” describes several software engineering failures that resulted in the loss of hundreds of millions of dollars and valuable scientific research in just the late 1990s. The paper also analyzes the factors in safety culture, management/organization, and technical deficiencies that contributed to these accidents. These include overarching issues like complacency, diffusion of responsibility, and poor communication as well as software engineering issues like unsatisfactory specifications, overcomplexity, and insufficient review processes. The paper goes on to describe methods to promote the avoidance of these issues, concludes with the proposal that complacency was the root cause of all of these issues, and that that complacency needs to be addressed by maintaining rigorous standards for testing and safety analysis.

The final example of software failure I will mention in this post is a prime example of the impact of software management, or more accurately mismanagement, in the success or failure of a software project, the FBI Virtual Case File and Sentinel projects. In the early 2000s the US FBI sought to transition to a modern case filing system, but the project was abandoned after 5 years and nearly $200 million and a new project, Sentinel, was started with the same goal, and after another 6 years and > 400 million dollars, was completed, although a 2014 audit revealed it was still facing ongoing issues. Audits of these projects determined that there were major issues relating to management and project specifications, and the projects stand as a case study of project mismanagement.

After analyzing these three sets of software failures it is clear that common themes begin to emerge. Inadequate planning, improper management, overcomplexity, unclear specifications, and lack of testing are perhaps the most pressing issues that lead to software failure, and it is evident that these issues must be addressed by project managers in order to avoid future software failures. The examples discussed in this post demonstrate that software projects simply cannot be rushed. They require clear specifications and management as well as thorough testing and analysis procedures. In short, we should learn from these past failures to employ good software engineering practices to help ensure failures like these are avoided in the future.
___

## References

This post is commentary on the following articles:

- [An Investigation of the Therac-25 Accidents](http://bowringj.people.cofc.edu/docs/therac-25.pdf)
- [The Role of Software in Spacecraft Accidents](http://bowringj.people.cofc.edu/classes/csci%20362/docs/levesonSoftwareAccidentsSpacecraft.pdf)
- [Who Killed the Virtual Case File?](http://bowringj.people.cofc.edu/classes/csci%20362/docs/SpectrumFBIcaseFileSytem.pdf)
- [FBI Sentinel project is over budget and behind schedule, say IG auditors](http://www.washingtonpost.com/wp-dyn/content/article/2010/10/20/AR2010102006754.html)
- [Years Late and Millions Over Budget, FBI's Sentinel Finally On Line](http://www.pcmag.com/article2/0,2817,2407922,00.asp)
- [FBI’s Sentinel System Still Not In Total Shape to Surveil](http://spectrum.ieee.org/riskfactor/computing/it/fbis-500-million-sentinel-case-management-system-still-has-major-operational-kinks-ig-reports)
- [Why Software Projects Fail, and the Traps You Can Avoid That Could Spell Disaster](https://www.entrepreneur.com/article/329019)
