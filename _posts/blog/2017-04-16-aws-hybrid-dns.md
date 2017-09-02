---
layout: post
title: "Hybrid DNS for the Enterprise in AWS"
excerpt: "Learnings and challenges from extending a hybrid DNS solution from an existing enterprise DNS environment into AWS."
categories: blog
tags: [aws, tutorial]
comments: false
share: true
modified: 2017-04-16 15:27:31
---

<p>AWS’ DNS offering, Route 53, is a great option for managing the basics of name resolution when resources exist solely within the AWS ecosystem. Route 53 integrates with most all of AWS’ services, offers great alias record functionality, and is easy to automate. However, for enterprises looking to make the move to AWS, especially in a hybrid deployment, Route 53 will most likely not be enough to provide all of the name resolution capabilities required. Because of this, hybrid DNS solutions need to be explored and implemented.</p>
<p>Through the rest of this post, I’ll explain some of the key areas to consider when planning your internal DNS strategy for moving to the cloud, as well as some learnings and challenges from previous DNS projects I’ve encountered. This post will focus on internal, private DNS zones.</p>

<a href="https://medium.com/@mda590/hybrid-dns-for-the-enterprise-in-aws-5ba5a049bcb1" title="Hybrid DNS for the Enterprise in AWS" target="_blank">Click here to read more!</a>