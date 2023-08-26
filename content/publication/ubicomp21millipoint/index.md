---
title: 3D Point Cloud Generation with Millimeter-Wave Radar

authors:
- Kun Qian
- Zhaoyuan He
- Xinyu Zhang

date: 2021-09-11T00:00:00.000Z
doi: ""

publishDate: 2021-04-15T21:31:49.759Z

publication_types:
  - "1"

publication: In Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (**IMWUT**) 2021
publication_short: In Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (**IMWUT**)

abstract: Emerging autonomous driving systems require reliable perception of 3D surroundings. Unfortunately, current mainstream perception modalities, i.e., camera and Lidar, are vulnerable under challenging lighting and weather conditions. On the other hand, despite their all-weather operations, today’s vehicle Radars are limited to location and speed detection. In this paper, we introduce MilliPoint, a practical system that advances the Radar sensing capability to generate 3D point clouds. The key design principle of MilliPoint lies in enabling synthetic aperture radar (SAR) imaging on low-cost commodity vehicle Radars. To this end, MilliPoint models the relation between signal variations and Radar movement, and enables self-tracking of Radar at wavelength-scale precision, thus realize coherent spatial sampling. Furthermore, MilliPoint solves the unique problem of specular reflection, by properly focusing on the targets with post-imaging processing. It also exploits the Radar’s built-in antenna array to estimate the height of reflecting points, and eventually generate 3D point clouds. We have implemented MilliPoint on a commodity vehicle Radar. Our evaluation results show that MilliPoint effectively combats motion errors and specular reflections, and can construct 3D point clouds with much higher density and resolution compared with the existing vehicle Radar solutions.

draft: false
featured: false

url_pdf: 'https://www.dropbox.com/s/eonykw3mu91j5rf/UbiComp21_MilliPoint_paper.pdf?dl=0'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://www.dropbox.com/s/nhabz3o4318b26o/UbiComp21_MilliPoint_slides.pptx?dl=0'
url_source: ''
url_video: ''

image:
  caption: "MilliPoint generates dense and well-structured point clouds using low-resolution radars."
  filename: featured
  focal_point: Smart
  preview_only: false
---
