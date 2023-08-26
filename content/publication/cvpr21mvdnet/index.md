---
title: Robust Multimodal Vehicle Detection in Foggy Weather using Complementary Lidar and Radar Signals

authors:
- Kun Qian
- Shilin Zhu
- Xinyu Zhang
- Li Erran Li

date: 2021-06-19T00:00:00.000Z
doi: ""

publishDate: 2021-04-15T21:31:49.759Z

publication_types:
  - "1"

publication: In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**) 2021
publication_short: In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**)

abstract: Vehicle detection with visual sensors like lidar and camera is one of the critical functions enabling autonomous driving. While they generate fine-grained point clouds or high-resolution images with rich information in good weather conditions, they fail in adverse weather (e.g., fog) where opaque particles distort lights and significantly reduce visibility. Thus, existing methods relying on lidar or camera experience significant performance degradation in rare but critical adverse weather conditions. To remedy this, we resort to exploiting complementary radar, which is less impacted by adverse weather and becomes prevalent on vehicles. In this paper, we present Multimodal Vehicle Detection Network (MVDNet), a two-stage deep fusion detector, which first generates proposals from two sensors and then fuses region-wise features between multimodal sensor streams to improve final detection results. To evaluate MVDNet, we create a procedurally generated training dataset based on the collected raw lidar and radar signals from the open-source Oxford Radar Robotcar. We show that the proposed MVDNet surpasses other state-of-the-art methods, notably in terms of Average Precision (AP), especially in adverse weather conditions. The code and data are available at https://github.com/qiank10/MVDNet.

tags:

draft: false
featured: false

url_pdf: 'https://www.dropbox.com/s/gl8mveo1i8w9re9/CVPR21_MVDNet_paper.pdf?dl=0'
url_code: 'https://github.com/qiank10/MVDNet'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://www.dropbox.com/s/wl3k3wsce1sfcfd/CVPR21_MVDNet_slides.pptx?dl=0'
url_source: ''
url_video: ''

image:
  caption: "MVDNet fuses both Lidar and Radar and overcomes their respective drawbacks."
  filename: featured
  focal_point: Smart
  preview_only: false
  
---
