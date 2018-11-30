---
title: "A Study of Hand Motion Trajectory Tracking by Utilizing Channel State Information of off-the-shelf Wi-Fi Devices"
collection: Conference
type: "Internaltional Conference (Poster)"
permalink: /talks/talk-2
venue: "Toyama International Conference Center and ANA Crowne Plaza Toyama"
date: 2018-08-01
location: "Toyama, Japan"
---

[More information here](http://www.piers.org/piers2018Toyama/)

<b> Abstract </b>
Technological advancement has changed the means of communication between human and computing devices from physical interaction (e.g. mouse and keyboard) to virtual interaction (e.g. motion tracking and gesture recognition). Latter applications mostly utilize optical devices which may subject to some limitations; small tracking coverage, surrounding light dependency, requirement of obstacle-free area, and privacy exposure. Since RF signal does not constraint by above limitations, various techniques of using channel state information (CSI) of commodity Wi-Fi devices to realize virtual interaction has been widely proposed to mitigate these issues. By utilizing CSI, although many works have shown a promising result in gesture recognition, it is still a challenge for implementation a motion tracking due to small bandwidth and non-synchronization issue. 

Therefore, the idea of this research is an attempt to indirectly track hand motion trajectory from a set of ``Hand Motion Profile'', a velocity pattern of hand moving from different angle, derived from both CSI amplitude and phase. In this paper, we initially focused only how to capture the profile of 1D horizontal hand movement which consist of 3 steps.  First, CSI streams during motion is segmented by considering variance of amplitude. Second, principle component analysis (PCA) is applied to select the segmented CSI stream influence the most by motion as well as separating CSI phase from residual offsets caused by hardware.  The profile is captured as the complex CSI reconstructed from preprocessed amplitude and phase which can be visualized as velocity pattern in Doppler-variant transfer function by taking Wavelet transform. In experiment, CSI was estimated from a transmission of random Wi-Fi packets while the hand motion was horizontally moved toward and away from receiver parallel to Line-of-Sight (LoS). The result shown that the sign of velocity is opposite between direction of motion and it is proportional to the change of signal propagation path while the pattern of velocity depicted the magnitude of speed.
