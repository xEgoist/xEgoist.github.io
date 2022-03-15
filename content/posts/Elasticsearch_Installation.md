---
title: "ElasticSearch 8.0 - Installation"
summary: Installation guide for ElasticSearch 8.0 and Fleet Configuration
date: 2022-03-06
weight: 4
aliases: ["/elastic-install"]
tags: ["ElasticSearch","Fleet", "Kibana", "Beats"]
author: "Moheeb Aljaroudi"
draft: true
---

# Introduction
With the recent update from Elastic, there have been many changes to the installation proccess and configuration, especially changes for a beat setup. 

In this guide, I will be showing how to install Elasticsearch, Kibana, and configure a Fleet Server.

If you wish to follow along this tutorial but want to deploy this server for eduaction/test purposes, you should be able to emulate this environment using a virtualization software (I would use Virt-Manager or UTM if you're using a Mac)

## Fleet
Elastic's new addition to the monitoring setup is the fleet server. With a Fleet configuration, you won't have to worry about updating the client side nor enabling client specific logs, the fleet server can take care of configuring, updating, and integrating the client with little interaction with them.

Because this setup is more convenient, this tutorial will guide you through the basics of the fleet server.

# Installation
I refuse to provide a copy of the download and installation instructions in my blog as there will eventually be changes in keys (You also shouldn't trust keys / repos given by a random blog).

Therefore, here is the official elastic link:

```HTML
https://www.elastic.co/guide/en/elasticsearch/reference/current/install-elasticsearch.html
```


Follow the official download guide, after you install elasticsearch and kibana, you can come back here to follow the rest of the instructions.


