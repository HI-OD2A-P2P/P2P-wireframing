---
title: "Scientific Data Transfer Examples"
teaching: 10
exercises: 0
question:
-
objectives:
-
---

# Proofs Of Concept

{% include figure.html url="" max-width="50%"
   file="/fig/ep70.png" width=500px alt="" caption="" %}

# Hawaii Guam Loop

<span style="color:#FFFFFF">2 performance test boxes in Hawaii\, connected to each other via GOREX</span>

<span style="color:#FFFFFF">13\,046 km packet travel\, each way\.</span>

<span style="color:#FFFFFF">Mellanox 100Gb Ethernet NICs</span>

<span style="color:#FFFFFF">AMD EPYC  7551 32\-core\, 128GB RAM</span>

<span style="color:#FFFFFF">16x10TB  \(160TB volume interleaved across 2 SAS3 controllers\)</span>

<span style="color:#FFFFFF">Currently moving 21 Gbps disk\-to\-disk between mdadm RAID0 volumes</span>

<span style="color:#FFFFFF">Zero drops/retransmissions</span>

{% include figure.html url="" max-width="50%"
   file="/fig/ep71.jpg" width=500px alt="" caption="" %}

# 21,897 km 100 Gbps Path

* MAX → GOREX → Hawaii
  * 21\,897 km one way
  * 284ms round trip time
  * round trip is longer in distance than circumnavigation at equator

{% include figure.html url="" max-width="50%"
   file="/fig/ep72.png" width=500px alt="" caption="" %}


__16 parallel wget\, each moving 32\, 2GB files__

__senders paced at 1Gbps per stream__

__Peak rate: 16\.0 Gbps\, Effective rate 7\.048Gbps__

__1 TB moved in 1 minute\, 18 seconds__

{% include links.md %}