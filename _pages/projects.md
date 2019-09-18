---
title: "Projects"
permalink: /projects/
author_profile: true
---

## Projects

<b>[ORACLE: Optimized Radio clAssification through Convolutional neuraL nEtworks](http://lantaoyu.com/publications/GanGradient)</b> <br>

Project Description:
This paper describes the architecture and performance of ORACLE, an approach for detecting a unique radio from a large pool of bit-similar devices (same hardware, protocol, physical address, MAC ID) using only IQ samples at the physical
layer. ORACLE trains a convolutional neural network (CNN) that balances computational time and accuracy, showing 99%
classification accuracy for a 16-node USRP X310 SDR testbed and an external database of >100 COTS WiFi devices. Our work
makes the following contributions: (i) it studies the hardwarecentric features within the transmitter chain that causes IQ
sample variations; (ii) for an idealized static channel environment, it proposes a CNN architecture requiring only raw IQ samples accessible at the front-end, without channel estimation or prior knowledge of the communication protocol; (iii) for dynamic channels, it demonstrates a principled method of feedback-driven transmitter-side modifications that uses channel estimation at the receiver to increase differentiability for the CNN classifier.
The key innovation here is to intentionally introduce controlled imperfections on the transmitter side through software directives, while minimizing the change in bit error rate. Unlike previous work that imposes constant environmental conditions, ORACLE adopts the ‘train once deploy anywhere’ paradigm with nearperfect device classification accuracy.




