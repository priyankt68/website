+++
title = "Software Versioning"
description = "Thoughts on modern software versioning and it's interplay with hardware"
date: 2018-01-06 18:00:00 +0000
tags = []
categories = []
+++

If you are writing any kind of software in today's world, it's imperative that you version your software.

Scott Adams in his iconic Dilbert comic says that [software is never finished](https://dilbert.com/strip/2017-10-02). What the comic argues that software development by definition is bound to incorporatte changes and will involve changes to occomodate either business needs as improvements or bug fixes which were initally not indentified during the course of testing inital release.

It's understood that software once released is bound to change. Having understood this, software developers version their software.

Software version has been a long standing practice which I'm sure emerged as a need. Necessity is the mother of invention.. Linus Torvalds while writing code for the [linux kernel](https://git-scm.com/book/en/v2/Getting-Started-A-Short-History-of-Git) realised the need to build a software versioning tool. This led to the development of today's most used tool - git - for software versioning in 2005. Read this Linux Journal [article](https://www.linuxjournal.com/content/git-origin-story) for a git origins story.

Modern software development involves [git](https://git-scm.com) as a de-facto source code versioning tool. It's not that git is the only option available to version source code but is the most widely accepted one. [Mercurial(Hg)](https://www.mercurial-scm.org) being another one. It's not necessary than one is [better](https://www.atlassian.com/blog/git/git-vs-mercurial-why-git) than the other in all aspects. Read [Steve Losh](http://stevelosh.com)' article on the [real difference between Mercurial and Git](http://stevelosh.com/blog/2010/01/the-real-difference-between-mercurial-and-git/) to better understand. Companies like Github, Atlassian and Gitlab have based their entire product lines on the concept of software versioning. It's certainly not a naive problem to solve and therefore you do see Github, Gitlab and Atlassian like giants existing in the market and [vying for market share](https://www.infoworld.com/article/3123244/application-development/enterprise-repo-wars-github-vs-gitlab-vs-bitbucket.html) but largely dominated by Github as per  [this](https://www.datanyze.com/market-share/source-code-management/git-market-share) report.

### Conventions

Versioning software involves versioning source code to distinguish feature sets. Agile development states that software releases incorporates group of feature sets released together and named as one release. There are several releases after the first release. These are generally termed as release milestones and companies have their traditional way of calling it out. Most companies have a release plan and abide by it for every product release.

Microsoft has a long standing tradition of naming it's early product releases as Preview.

While Google and other companies alike call it Alpha, Beta releases. 

Side note - If you're interested in release planning, I like how Mozilla details on release engineering in their [wiki](https://wiki.mozilla.org/ReleaseEngineering). It's a release plan which is followed for all of their open source contributions.

These releases distinctions are largely around the target audience it's intended for. For instance, most Preview or Beta releases by companies are intended for the early adopters. [Early adopters](https://en.wikipedia.org/wiki/Early_adopter), review and crtically analyse the software. They are generally okay with bugs or non-functioning of certain features and are willing to experiment your product. Most companies deliberatly ship Preview/Beta release to test market acceptance and get early feedback. It's a good way to test out whether your release was okay with the known bugs or limitations or not. <insert a link of a practice in product engineering if there exists one related to feedback or early adopters>.

A deeper sense of versioning software is related to [semantic versioning](https://semver.org). This is largely the versioning conventions which is targeted for software developers and perhaps other softwares which depend on the software being released. The audience which reads these releases are developers who are using their product. Semantic versioning involves following three key components to it's schema

`MAJOR.MINOR.PATCH` 

###(Soft,Hard)Ware versioning

Having worked in the IoT domain for the last 5 years, I've accumuated some sense of versioning software which works in tandem with hardware versioning. A hardware version can refer to the kind of chipset it's built with. This chipset and other components associated with the hardware may determine the kind of software(or firmware) that can run on the hardware. This leads to another level of complexity which entails software versioning with respect to the hardware versioning.

 A hardware version, semantically labelled as 1.1 may only work with software version 0.1 and therefore the developer cannot upgrade software(typically called firmware in the industry) beyond 0.1. 

This is IMO an extension of semantic versioning of software and nature of it's dependencies. A software or firmware versioning is inter-linked with the hardware version as well. This is not a big problem when dealing with virtualised hardware - largely true for the software running on cloud but becomes an increasingly important problem for the software or firmware running as close to the hardware. Essentially, closer you get to the hardware, more one needs to worry about the software and hardware versioning dependencies.
