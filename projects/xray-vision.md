---
layout: project
type: project
image: img/paperGIF.gif.gif
title: "Training for X-Ray Vision: Amodal Segmentation, Amodal Content Completion, and View-Invariant Object Representation from Multi-Camera Video"
date: July 2 2025
published: true
labels:
  - Computer Vision
summary: "Co-Authored a Arxiv Preprint That Published MOVi-MC-AC: Multiple Object Video with Multi-Cameras and Amodal Content, the largest amodal segmentation and first amodal content dataset to date. "
---


<div style="text-align: center; margin: 20px 0;">
  <a href="https://arxiv.org/pdf/2507.00339" target="_blank" class="btn btn-primary">📄 View Paper on ArXiv</a>
  <a href="https://huggingface.co/datasets/Amar-S/MOVi-MC-AC" target="_blank" class="btn btn-secondary">🤗 Access Dataset</a>
</div>

Abstract: Amodal segmentation and amodal content completion require using object priors to estimate occluded masks and features of objects in complex scenes. Until now, no data has provided an additional dimension for object context: the possibility of multiple cameras sharing a view of a scene. We introduce MOVi-MC-AC: Multiple Object Video with Multi-Cameras and Amodal Content, the largest amodal segmentation and first amodal content dataset to date. Cluttered scenes of generic household objects are simulated in multi-camera video. MOVi-MC-AC contributes to the growing literature of object detection, tracking, and segmentation by including two new contributions to the deep learning for computer vision world. Multiple Camera (MC) settings where objects can be identified and tracked between various unique camera perspectives are rare in both synthetic and real-world video. We introduce a new complexity to synthetic video by providing consistent object ids for detections and segmentations between both frames and multiple cameras each with unique features and motion patterns on a single scene. Amodal Content (AC) is a reconstructive task in which models predict the appearance of target objects through occlusions. In the amodal segmentation literature, some datasets have been released with amodal detection, tracking, and segmentation labels. While other methods rely on slow cut-and-paste schemes to generate amodal content pseudo-labels, they do not account for natural occlusions present in the modal masks. MOVi-MC-AC provides labels for ~5.8 million object instances, setting a new maximum in the amodal dataset literature, along with being the first to provide ground-truth amodal content. The full dataset is available at https://huggingface.co/datasets/Amar-S/MOVi-MC-AC ,
