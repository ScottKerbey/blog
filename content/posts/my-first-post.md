---
title: "Starting My Blog"
date: 2020-01-11T21:40:08+08:00
draft: false
---

I've started this blog to document some of my personal projects around machine learning/AI and cloud computing.

Some old projects will probably get cleaned up and moved onto here and some new project will appear.

This post is to demonstrate my first new project: This blog!

I was investigating how to best start a blog using a cloud provider and after much frustration trying to set up wordpress in Azure i fell back on plan B.
Static Websites. It turns out this is much cheaper and really easy to use.

Initially I deployed in Azure. [This](https://azure.microsoft.com/en-au/blog/static-websites-on-azure-storage-now-generally-available/) Azure guide was useful.
However since my Azure account is provided to me by my employer and could be lost I decided to set up a more permanent deployment on AWS.
[This](https://docs.aws.amazon.com/AmazonS3/latest/dev/HostingWebsiteOnS3Setup.html) AWS guide was useful and even easier to follow.

Both guides follow a similar procedure:
1. Create a storage container (Azure: storage account, AWS: S3 bucket)
2. Enable Static Website
3. Upload files

That's all you need to set up a static website. Additional steps can be performed to set a custom domain name.

As for building the blog itself I found [Hugo](https://gohugo.io/). It's a static site generator that is relly easy to use.