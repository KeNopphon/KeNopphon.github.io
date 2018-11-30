---
title: "Tracking 1D Hand Motion Directivity by Estimating Doppler Frequency of CSI Information from Commodity Wi-Fi Devices"
collection: Technical Report in Microwave
type: "IEICE Workshop"
permalink: /talks/talk-1
venue: "Kokushikan University"
date: 2017-12-19
location: "Tokyo, Japan"
---


[More information here](https://www.ieice.org/ken/paper/20171219F1a0/eng/)

<b> Abstract </b>
Device-free hand motion tracking in the air becomes an essential tool for today human-computing interaction applications such as smart home, virtual and augmented reality. Typical tracking, mostly a camera-based application, has some limitations; small tracking coverage, surrounding light dependency, and requirement of obstacle-free area. In this report, we show the possibility of tracking 1D hand motion by exploiting channel state information (CSI) from commercial Wi-Fi infrastructure. Empirically, it was proved that, after removing linear phase offset, sanitized CSI could be sufficiently reconstructed from its sanitized phase and amplitude where motion pattern and directivity are well-preserved. In the experiment, the velocity profile of hand moving toward and away from Wi-Fi receiver was retrieved as a temporal-Doppler representation by taking Wavelet transform of sanitized CSI. Moreover, it was found that this motion pattern, unfortunately, could be able to retrieve at only some subcarriers. According to our observation, it is possibly due to amplitude fading and an anomaly phase jump during sanitization resulting in directivity losing after reconstruction of Sanitized CSI.