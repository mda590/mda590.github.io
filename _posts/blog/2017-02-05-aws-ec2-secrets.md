---
layout: post
title: "Simple Secrets Management via the AWS EC2 Parameter Store"
excerpt: "Amazon’s EC2 Systems Manager was launched at re:Invent 2016. It brings with it a lot of very useful tools meant to ease the administration and management of your EC2 instances and associated resources."
categories: blog
tags: [aws, tutorial]
comments: false
share: true
modified: 2017-02-05 15:27:31
---

<p>Amazon’s EC2 Systems Manager was launched at re:Invent 2016. It brings with it a lot of very useful tools meant to ease the administration and management of your EC2 instances and associated resources. One part of the EC2 Systems Manager suite is the Parameter Store. I think the Parameter Store is actually really quite powerful and can help secure your AWS environment in ways that may not be initially obvious.</p>
<p>The Parameter Store offers the ability to store 3 different types of data, which can then be programmatically accessed via the SSM API. The 3 types of data are: String, String List, and Secure String. In this post, I want to concentrate on the “Secure String” option and how it can be used to store and retrieve secrets within your AWS environment.</p>

<a href="https://medium.com/@mda590/simple-secrets-management-via-aws-ec2-parameter-store-737477e19450#.p678on280" title="Simple Secrets Management via the AWS EC2 Parameter Store" target="_blank">Click here to read more!</a>