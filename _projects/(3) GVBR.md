---
name: Improving Video Steaming
tools: [QoS]
image: 
description: This project aims to improve video steaming on the broadcaster side.
---

# GVBR

Ensuring high video quality of experience (QoE) on the broadcaster side is critical for interactive live streaming. However, measurements on multiple live streaming platforms show that they all suffer from broadcaster-side video quality degradation in the presence of transient bandwidth fluctuations. This project presents Greedy Variable Bitrate (GVBR), a suite of solutions that optimizes the QoE through an appropriate keyframe interval that trades cross-frame compression for lowered inter-frame interdependency, a simple-yet-efficient frame dropping strategy to prevent excessive frame drops, and a bitrate adaptation strategy customized for broadcasters who have shallow buffer. We compare GVBR with state-of- art algorithms in different network conditions, and find that GVBR can cut video interruption incidents by 90%, while achieving comparable bitrate. 

More details in IWQoS'18 paper [[pdf]](https://hongyi-huang.github.io/files/GVBR.pdf).