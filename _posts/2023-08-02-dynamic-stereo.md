---
title: "Dynamic Programming for Stereo Reconstruction"
thumbnail: "/assets/img/stereo.png"
description: "This project involves stereo image reconstruction using dynamic programming. The goal is to compute the Disparity Space Image (DSI) for two stereo images and apply dynamic programming to find the minimum-cost path, resulting in an accurate disparity map for depth estimation. 
<hr>
The process begins with converting the stereo images into grayscale and computing the DSI using Normalized Cross Correlation (NCC) for each row. Dynamic programming is then applied to identify the optimal path through the DSI, from the top-left corner to the bottom-right. After back-tracing the path, the disparity is computed, and the process is repeated for each row. Occlusions are filled in the final step to complete the stereo reconstruction.

This project provides a deeper understanding of stereo vision and dynamic programming techniques for computer vision tasks."
technologies: ["Python", "Dynamic Programming", "Normalized Cross Correlation", "Stereo Vision"]
github_link: "https://github.com/progga004/Dynamic-Programming-for-Stereo-Reconstruction/tree/main"
demo_link: "Still to come"
---
