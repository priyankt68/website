---
author: Priyank Trivedi
date: 2017-02-26 00:00:00 +0000
linktitle: GopherCon India 2017 Recap
title: GopherCon India 2017 Recap
highlight: true
type: blog-post
tags:
- review
- conference
publish_data: 2017-02-26 02:00:00 +0530
gallery: []
body: ''
figure: ''
draft: true

---

3:30 am flight to Pune - just to optimise on the cost and time! Awesome. Totally worth it.

The GopherCon India 2017 was extremely well organised by Emerging Technology Trust with an excellent Master of Ceremony- [Gautam Rege](https://twitter.com/gautamrege). The conference began with a keynote talk by Frances on “context” package and was followed by several interesting talks on a variety of topics. Overall there existed a good mix of architecture as well as implementation level talks.
It was the third edition of GopherCon India attended by close to 300 delegates with representation from 12 countries.

## Key Talks

Following are some of the talks which I particularly liked.

* Building Distributed Timeseries Database in Go by Matthew Campbell - [Talk Slides](https://speakerdeck.com/mattkanwisher/building-distributed-timeseries-database-in-go)

* Flogo - A Golang-powered Open Source IoT Integration Framework by Kai Wähner - [Talk slides](http://www.slideshare.net/KaiWaehner/flogo-a-golangpowered-open-source-iot-integration-framework-gophercon)

## My Lightning Talk - [Server Monitoring using Influxdata](https://twitter.com/ApsOps/status/835085984723263489)

I got an opportunity to give a lightning talk on 'Server Monitoring using Influxdata'. I detailed about how at [Zenatix](https://zenatix.com), we're using Influxdata's TICK stack for monitoring our servers with right alerts in place.
I followed it up with demonstrating some Golang code for writing a Telegraf plugins. [Talk slides](https://speakerdeck.com/priyankt68/server-monitoring-using-influxdata)

<script async class="speakerdeck-embed" data-id="71788448a40449138313bd5d25e9b460" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>

## Key Projects Takeaway

My discussions around projects revolved around IoT and Data Analytics. Following are some of the good projects that I'd like to try out in-depth.

* [Flogo](https://flogo.io) - Open source project written in Go for IoT integration. It's a project released under [BSD-style license](https://github.com/TIBCOSoftware/flogo/blob/master/LICENSE.txt). It's definitely one of the projects that I would like to explore from the architecture standpoint.

* [Gobots](https://gobot.io) - I came to know about this through on my hallway discussions.

* [Vulcan](https://github.com/digitalocean/vulcan) - Matthew is his talk detailed on how they built Vulcan on top of Prometheus at DigitalOcean. This [issue](https://github.com/digitalocean/vulcan/issues/45) on GitHub details on why Vulcan exists.

## The Hallway Tracks

These are tracks which happen when you’re interacting with attendees in the hallways. One of the core reasons why attend most conferences!

In these 'tracks', I discuss about the problem we're solving at [Zenatix](https://zenatix.com) and also get a perspective on what others think about it.

I had an amazing discussion with [William Kennedy](https://twitter.com/@goinggodotnet) on writing a proposal document before planning any feature/bug. According to him, one should try to bring in `“Why”` before writing any line of code.

According to him, while writing a proposal document, outline it in the following manner.

1. History of the problem - Give users a flavor of the problem with information around the problem. This is more like the literature survey in academic publications.

1. Problem definition and why you’re solving it. -  Mention the core of the problem and reasons for solving it.

1. How we’re solving - Details on how we're going to solve it.

I highly recommend everyone to read his [blog](https://www.goinggo.net/2017/01/develop-your-design-philosophy.html).

## Overall Experience

I had a tremendous learning experience at GopherCon India. The GoLang community in India is pretty young. There is a lot that needs to be done to spread the magic of Go around.
I believe conferences such as these are one of key factors in determining the success of the community. Kudos to everyone involved with GopherCon India 2017.