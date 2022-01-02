---
title: "Inside the AWS re:Invent Session Bot"
date: 2018-11-23T00:00:00-05:00
draft: false
author: "Matt Adorjan"
tags:
- aws
- architecture
---

Today, I posted the code which runs the re:Invent Bot session tracking service. At a high level, this service scrapes the re:Invent session catalog at regular intervals, stores session information in a database, and then if sessions are new or changed, a Tweet is sent out with the session information.

The goal of this post is to provide an inside look at the re:Invent Bot and share some of the AWS architecture which powers it.

[Click here to read more!](https://medium.com/@mda590/inside-the-aws-re-invent-session-bot-c353830e2104)