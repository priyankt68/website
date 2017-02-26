---
author: "Priyank Trivedi"
date: 2017-02-26
linktitle: GopherCon India 2017 Recap
title: GopherCon India 2017 Recap
highlight: true
---

3:30 am flight to Pune - just to optimise the cost and time! Awesome. Totally worth it.

The GopherCon India 2017 was extremely well organised by Emerging Technology Trust with an excellent Master of Ceremony- Gautam Rege. The conference began with a keynote talk by Frances on “context” package and was followed by several interesting talks on a variety of topics. Overall there existed a good mix of architecture as well as implementation level talks.

## The Hallway Tracks 
These are the tracks which happen when you’re interacting with attendees in the hallways. One of the core reasons why attend most conferences!

Had an amazing discussion with William Kennedy on writing a proposal document before planning any feature/bug. According to him, one should try to bring in ```“Why”``` before writing any line of code.

According to him, while writing a proposal document, outline it in the following manner.

1. History of the problem - Give users a flavor of the problem with information around the problem. This is more like the literature survey in academic publications. 
2. Problem definition and why you’re solving it. -  Mention the core of the problem and reasons for solving it.
3.  How we’re solving - Details on how we're going to solve it.
 
I highly recommend everyone to read his blog -  


## Key Talks 

Following are some of the talk which were of key interests to me.

- Fast and Scalable Machine Learning with GoLang by Vidyasagar Nallapati - [Talk slides](https://speakerdeck.com/doctorandabox/fast-and-scalable-machine-learning-with-golang)
- Building Distributed Timeseries Database in Go by Matthew Campbell - [Talk Slides](https://speakerdeck.com/mattkanwisher/building-distributed-timeseries-database-in-go)
- "Flogo - A Golang-powered Open Source IoT Integration Framework by Kai Wähner - [Talk slides](http://www.slideshare.net/KaiWaehner/flogo-a-golangpowered-open-source-iot-integration-framework-gophercon)

## Key Projects Takeaway

My discussions around projects revolved around IoT and Data Analytics. Following are some of the good projects that I'd like to try out in-depth.

- [Flogo](https://flogo.io) - Open source project written in Go for IoT integration. It's a project released under [BSD-style license](https://github.com/TIBCOSoftware/flogo/blob/master/LICENSE.txt). It's definitely one of the projects that I would like to explore from the architecture standpoint. 
- [Gobots](https://gobot.io) - I came to know about this through on my hallway discussions. 
- [Vulcan](https://github.com/digitalocean/vulcan) - Matthew is his talk about how at DigitalOcean they built Vulcan on top of Prometheus. This [issue](https://github.com/digitalocean/vulcan/issues/45) on GitHub details on why Vulcan exists. 

## My Lighting Talk - [Server Monitoring using Influxdata](https://twitter.com/ApsOps/status/835085984723263489) 

I got an opportunity to give a lightning talk on Server Monitoring using Influxdata. I detailed about we're using Influxdata's TICK stack for monitoring our servers with right alerts in place.
I followed it up with demonstrating some Go code for writing a Telegraf plugin. [Talk slides](https://speakerdeck.com/priyankt68/server-monitoring-using-influxdata)


## Overall Experience

I had a tremendous learning experience at GopherCon India. The GoLang community in India still very young and there's a lot that needs to be done to spread the magic of Go around. 
I believe conferences such as these are one of key factors in determining the success of the community. Kudos to everyone involved with GopherCon India 2017. 

