---
title: 'Multi-view 2D-to-3D Self-Supervised Knowledge Distillation via Multi-Modality Masked Autoencoder'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yingwei Li
  - Longlong Jing
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

abstract: As 3D data is expensive and tedious to collect, some works have been proposed to distill 2D knowledge from 2D pre-trained models to 3D representations. However, we find that those 2D-3D knowledge distillation methods suffer from several shortcomings. First, the 2D encoded teacher feature from a perspective view is less informative than the 3D encoded student feature, making the distillation less effective; second, it is challenging to perfectly align the 2D image and 3D point cloud in feature level, which is important to the existing distillation methods. To address the first issue regarding the relatively less informative 2D encoded feature, we propose a multi-view strategy to distill the knowledge from 2D to 3D. To address the second issue regarding the difficulty of the feature-level alignment, we propose a 3D-to-2D feature-level reconstruction task, which allows for implicit 3D-to-2D alignment. Specifically, this method uses the visible encoded tokens of the 3D model to recreate the fully 2D features, thereby aligning the 3D and 2D information. Our experiments illustrate the effectiveness of the proposed self-supervised learning strategy for different tasks and under different settings. For instance, under the common linear SVM protocol, we achieve 93.2% on ModelNet40. By fine-tuning on the OBJ-ONLY split of ScanObjectNN, we achieve a 2.07% improvement compared to the prior state-of-the-art method, Point-M2AE.

# Summary. An optional shortened abstract.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

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

