---
layout: post
title:  "Progressive Face Super-Resolution via Attention to Facial Landmark"
date:   2019
excerpt: "BMVC (2019)"
tag:
- Face super-resolution
- Computer Vision
comments: false
---

<center><b>paper</b> </center> abstract <hr>
Face Super-Resolution (SR) is a subfield of the SR domain that specifically targets the reconstruction of face images. The main challenge of face SR is to restore essential facial features without distortion. We propose a novel face SR method that generates photo-realistic 8x super-resolved face images with fully retained facial details. To that end, we adopt a progressive training method, which allows stable training by splitting the network into successive steps, each producing output with a progressively higher resolution. We also propose a novel facial attention loss and apply it at each step to focus on restoring facial attributes in greater details by multiplying the pixel difference and heatmap values. Lastly, we propose a compressed version of the state-of-the-art face alignment network (FAN) for landmark heatmap extraction. With the proposed FAN, we can extract the heatmaps suitable for face SR and also reduce the overall training time. Experimental results verify that our method outperforms state-of-the-art methods in both qualitative and quantitative measurements, especially in perceptual quality.

<a href="https://arxiv.org/abs/1908.08239">PDF</a> <a href="https://github.com/DeokyunKim/Progressive-Face-Super-Resolution">Code</a>
 
