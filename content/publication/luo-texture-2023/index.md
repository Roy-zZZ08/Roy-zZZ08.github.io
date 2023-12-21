---
title: Texture Atlas Compression Based on Repeated Content Removal

authors:
- Yuzhe Luo
- Xiaogang Jin
- Zherong Pan
- Kui Wu
- Qilong Kou
- Xiajun Yang
- Xifeng Gao

date: '2023-12-01'

publishDate: '2023-12-20T16:02:25.140213Z'

publication_types:
- paper-conference

publication: '*SIGGRAPH Asia 2023 Conference Papers*'

abstract: Optimizing the memory footprint of 3D models can have a major impact on the user experiences during real-time rendering and streaming visualization, where the major memory overhead lies in high-resolution texture data. In this work, we propose a robust and automatic pipeline to content-aware, lossy compression for texture atlas. The design of our solution lies in two observations- 1) mapping multiple surface patches to the same texture region is seamlessly compatible with the standard rendering pipeline, requiring no decompression before any usage; 2) a texture image has background regions and salient structural features, which can be handled separately to achieve a high compression rate. Accordingly, our method contains three phases. We first factor out redundant salient texture contents by detecting such regions and mapping their corresponding 3D surface patches to a single UV patch via a UV-preserving re-meshing procedure. We then compress redundant background content by clustering triangles into groups by their color. Finally, we create a new UV atlas with all repetitive texture contents removed and bake a new texture via differentiable rendering to remove potential inter-patch artifacts. To evaluate the efficacy of our approach, we batch-processed a dataset containing 100 models collected online. On average, our method achieves a texture atlas compression ratio of 81.80% with an averaged PSNR and MS-SSIM scores of 40.68 and 0.97, a marginal error in visual appearance.

doi: 10.1145/3610548.3618150

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: true

url_pdf: ''
url_code: 'https://github.com/Roy-zZZ08/Texture-Atlas-Compression'
url_video: 'https://www.youtube.com/watch?v=V0DeDZJIgLY'

links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3610548.3618150
---
