---
title: 'Point Cloud Self-supervised Learning via 3D to Multi-view Masked Autoencoder'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yingwei Li
  - Longlong Jing
  - Liang Yang
  - Bing Li

date: '2023-09-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication:
publication_short: Submit to *CVPR, 2024*

abstract: In recent years, the field of 3D self-supervised learning has witnessed significant progress, resulting in the emergence of multi-modality masked autoencoders (MAE) methods that leverage both 2D images and 3D point clouds for pre-training. However, a notable limitation of these approaches is that they do not fully utilize the multi-view attributes inherent in 3D point clouds, which is crucial for a deeper understanding of 3D structures. Building upon this insight, we introduce a novel approach employing a 3D to multi-view masked autoencoder to fully harness the multi-modal attributes of 3D point clouds. To be specific, our method uses the encoded tokens from 3D masked point clouds to generate original point clouds and multi-view depth images across various poses. This approach not only enriches the model's comprehension of geometric structures but also leverages the inherent multi-modal properties of point clouds. Our experiments illustrate the effectiveness of the proposed method for different tasks and under different settings. Remarkably, our method outperforms state-of-the-art counterparts by a large margin in a variety of downstream tasks, including 3D object classification, few-shot learning, part segmentation, and 3D object detection.

# Summary. An optional shortened abstract.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/abs/2311.10887
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.

---

