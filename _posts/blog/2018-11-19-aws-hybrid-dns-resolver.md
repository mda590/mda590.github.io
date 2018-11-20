---
layout: post
title: "Introducing Route 53 Resolver for Hybrid Cloud"
excerpt: "This post will review the functionality introduced in the new Route 53 Resolver for Hybrid Cloud offering, how to use it, and how to transition away from an EC2 based DNS forwarder solution to using only AWS' new managed Route 53 services."
categories: blog
tags: [aws, tutorial]
comments: false
share: true
modified: 2018-11-19 10:00:00
---

<p>Early last year, <a href="https://medium.com/statuscode/hybrid-dns-for-the-enterprise-in-aws-5ba5a049bcb1">I published an article</a> outlining the different options available for creating an enterprise-tailored hybrid DNS solution on AWS. This solution required EC2 instances, configuring DNS software, and a good amount of "undifferentiated heavy lifting."</p>
<p>As AWS has matured their enterprise offerings over the past several years, they've identified hybrid DNS as a gap and I was so happy to hear they've solved this problem by announcing the 'Route 53 Resolver for Hybrid Cloud' service today!</p>
<p>The new Route 53 resolver offering is broken down into two different offerings - an "inbound endpoint" and an "outbound endpoint". When used together, an enterprise has all of the pieces required to turn an existing DNS configuration into a hybrid configuration, bridging both the datacenter and AWS.</p>
<p>This post will review the functionality introduced in the new Route 53 Resolver for Hybrid Cloud offering, how to use it, and how to transition away from an EC2 based DNS forwarder solution to using only AWS' new managed Route 53 services!</p>

<a href="https://medium.com/@mda590/an-update-to-hybrid-dns-for-the-enterprise-on-aws-introducing-route-53-resolver-for-hybrid-cloud-74e55d4e67a2" title="An Update to Hybrid DNS for the Enterprise on AWS - Introducing Route 53 Resolver for Hybrid Cloud!" target="_blank">Click here to read more!</a>