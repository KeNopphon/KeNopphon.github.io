---
title: "Utilizing Doppler Frequency of Wi-F Channel State Informaton to Trace Trajectory of Hand Gesture"
collection: Conference
type: "Internatioanl Conference (Oral)"
permalink: /talks/talk-5
venue: "The University of Electro-Communications"
date: 2019-06-05
location: "Tokyo, Japan"
---

[More information here](http://www.ursi.jp/conference/jrsm2019/)

<b> Abstract </b>
One of alternative solution for the non-intrusive motion sensing is to use radio frequency (RF) signal which is more ubiquitous than commercial vision-based sensing. Analysis of Doppler frequency extracted from channel state information (CSI) of Wi-Fi chips is one of the RF-based sensing applications. While many studies could acceptably recognize a set of hand gesture using the pattern matching technique, their results could worsen drastically when gesture is performed at different positions. In this work, we propose the different hand sensing method that can handle the location-dependent issue. This approach focuses on the tracing of motion trajectory by observing time-varying Doppler frequency profile captured from different pairs of Wi-Fi antenna operating on multiple-input-multiple-output (MIMO) configuration. 
Typically, the interaction of Wi-Fi signal on moving object will cause Doppler frequency shift which can be observed by applying short-time Fourier transform (STFT) on CSI. However, the high resolution of Doppler profile comes with the cost of losing the time resolution according to uncertainty principle. Therefore, the Root-MUSIC [1] is utilized to approximately yield a super-resolution of Doppler profile given a better time resolution than STFT as shown in Figure 1. According to bistatic Doppler model [2], speed and motion direction can be estimated from the extracted Doppler profiles given the knowledge of Wi-Fi antenna positions. The gesture trajectory in 3D space is then estimated by taking the integral over direction of motion.  
To validate this concept, the initial position of hand and location of each Wi-Fi antenna were placed as mesh grid and points respectively in the simulation environment. Deterministic Doppler CSI model [3] was used to simulate Doppler frequency due to hand gesture (rectangular shape) of RF signal propagated at the frequency of 5.32 GHz with 40 MHz bandwidth. After applying the proposed method, the result in Figure 2 shows that the reconstructed gesture (orange line with marker), though with a wrong orientation, could restore the shape similar to the reference (blue line) with a small distortion. 	
