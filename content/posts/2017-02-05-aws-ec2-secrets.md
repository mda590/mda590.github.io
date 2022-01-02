---
title: "Simple Secrets Management via AWS EC2 Parameter Store"
date: 2017-02-05T00:00:00-05:00
draft: false
author: "Matt Adorjan"
tags:
- aws
- tutorial
---

Amazon’s EC2 Systems Manager was launched at re:Invent 2016. It brings with it a lot of very useful tools meant to ease the administration and management of your EC2 instances and associated resources. One part of the EC2 Systems Manager suite is the Parameter Store. I think the Parameter Store is actually really quite powerful and can help secure your AWS environment in ways that may not be initially obvious.

The Parameter Store offers the ability to store 3 different types of data, which can then be programmatically accessed via the SSM API. The 3 types of data are: String, String List, and Secure String. In this post, I want to concentrate on the “Secure String” option and how it can be used to store and retrieve secrets within your AWS environment.

[Click here to read more!](https://medium.com/@mda590/simple-secrets-management-via-aws-ec2-parameter-store-737477e19450#.p678on280)