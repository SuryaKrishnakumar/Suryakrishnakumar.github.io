---
layout: post
title: Bachelor's Thesis
author: "KN"
output:
  html_document:
    keep_md: true
tags: [Thesis, EME, Multimedia Processing, Video Coding, HEVC, H.265]
---

> My Bachelor's Thesis was on Multimedia Processing. It primarily dealt with High Efficiency Video Coding (HEVC) a.k.a H.265

The purpose of my Thesis was to develop an efficient algorithm for Fast Block Motion Estimation in H.265 (HEVC).

The Motion Estimation is an indispensable module in the design of any video encoder. It takes up 70% to 80% of the total video encoding time involving a Block Matching Algorithm to search for the desired candidate blocks in the reference frame. The Thesis involved defining a new and efficient algorithm which was compared with the the predominantly used search techniques like Full Search, Diamond Search, Cross Diamond Search, Efficient Two Step Search and Novel Hexagon Search techniques. Our EME algorithm delivered efficient results compared to the existing optimal and sub-optimal fast BMA.

### Actual Work:

Prediction and Refinement are two steps involved in the proposed algorithm. The prediction step weighs two parameters such as the temporal correlation and the direction to predict the MV of the candidate block. The refinement step makes use of several search patterns obtained through distinct combinations of search points. The experiments were conducted on standard SIF and CIF vide sequences. The results were tabulated and it was inferred that the Efficient Motion Estimation (EME) algorithm renders a faster search comparatively minimizing the total computational time.

### Related Publications:

- This work was presented on [Fourth IEEE International Conference on Recent Trends in Information Technology](https://www.annauniv.edu/ICRTIT2014/).

- It was then published as a Book Chapter in [Emerging Technologies in Intelligent Applications for Image and Video Processing](http://www.igi-global.com/chapter/an-efficient-algorithm-for-fast-block-motion-estimation-in-high-efficiency-video-coding/143559)
