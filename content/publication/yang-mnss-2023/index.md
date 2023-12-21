---
title: 'MNSS: Neural Supersampling Framework for Real-Time Rendering on Mobile Devices'
authors:
- Sipeng Yang
- Yunlu Zhao
- Yuzhe Luo
- He Wang
- Hongyu Sun
- Chen Li
- Binghuang Cai
- Xiaogang Jin
date: '2023-01-01'
publishDate: '2023-12-20T16:15:43.055880Z'
publication_types:
- article-journal
publication: '*IEEE Trans. Visual. Comput. Graphics*'
doi: 10.1109/TVCG.2023.3259141
abstract: Although neural supersampling has achieved great success in various applications
  for improving image quality, it is still difficult to apply it to a wide range of
  real-time rendering applications due to the high computational power demand. Most
  existing methods are computationally expensive and require high-performance hardware,
  preventing their use on platforms with limited hardware, such as smartphones. To
  this end, we propose a new supersampling framework for real-time rendering applications
  to reconstruct a high-quality image out of a low-resolution one, which is sufficiently
  lightweight to run on smartphones within a real-time budget. Our model takes as
  input the renderer-generated low resolution content and produces high resolution
  and anti-aliased results. To maximize sampling efficiency, we propose using an alternate
  sub-pixel sample pattern during the rasterization process. This allows us to create
  a relatively small reconstruction model while maintaining high image quality. By
  accumulating new samples into a high-resolution history buffer, an efficient history
  check and re-usage scheme is introduced to improve temporal stability. To our knowledge,
  this is the first research in pushing real-time neural supersampling on mobile devices.
  Due to the absence of training data, we present a new dataset containing 57 training
  and test sequences from three game scenes. Furthermore, based on the rendered motion
  vectors and a visual perception study, we introduce a new metric called inter-frame
  structural similarity (IF-SSIM) to quantitatively measure the temporal stability
  of rendered videos. Extensive evaluations demonstrate that our supersampling model
  outperforms existing or alternative solutions in both performance and temporal stability.

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

links:
- name: URL
  url: https://ieeexplore.ieee.org/document/10076842/

# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'
---
