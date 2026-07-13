---
title: "Image creation and testing with HashiCorp Packer and ServerSpec"
url: "https://medium.com/sumup-engineering/image-creation-and-testing-with-hashicorp-packer-and-serverspec-bb2bd065441?source=rss----bc8d70b3a259---4"
date: "2018-12-01"
author: "Anton Antonov"
feed_url: "https://medium.com/feed/sumup-engineering"
---
Using HashiCorp Packer and ServerSpec Intro At SumUp we use various technologies and tools depending on their purpose and trade-offs. Recently we started a few infrastructure-heavy projects. We had to solve the problem of creating images (virtual appliances) for QEMU and VirtualBox for multiple projects: one project creates guests using a chain of QEMU images one project creates guest using a chain of VirtualBox images What this article is going to cover as “hands-on” tech HashiCorp Packer (v1.3.x) ServerSpec ( v2.41.
