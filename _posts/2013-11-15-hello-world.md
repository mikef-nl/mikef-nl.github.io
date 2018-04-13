---
layout: post
title: Ansible Role Testing
categories: [general, ansible]
tags: [testing, ansible]
fullview: true
comments: true
---

So as part of day to day work I have Ansible for configuration management. While using Ansible roles for managing machine config I realized that what was needed was a way to test them.

Since GitLab is used as my source control it made sense to make use of it's CI features to automatically test roles on commits.

### The setup


