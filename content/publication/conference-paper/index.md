---
title: 'Bridging the Domain Gap: Self-Supervised 3D Scene Understanding with Foundation Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Longlong Jing
  - Yingwei Li
  - Bing Li


date: '2023-05-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Advances on Neural Information Processing Systems (NeurIPS)
publication_short: In *NeurIPS, 2023*

abstract: Foundation models have made significant strides in 2D and language tasks such as image segmentation, object detection, and visual-language understanding. Nevertheless, their potential to enhance 3D scene representation learning remains largely untapped due to the domain gap. In this paper, we propose an innovative methodology Bridge3D to address this gap, pre-training 3D models using features, semantic masks, and captions sourced from foundation models. Specifically, our approach utilizes semantic masks from these models to guide the masking and reconstruction process in the masked autoencoder. This strategy enables the network to concentrate more on foreground objects, thereby enhancing 3D representation learning. Additionally, we bridge the 3D-text gap at the scene level by harnessing image captioning foundation models. To further facilitate knowledge distillation from well-learned 2D and text representations to the 3D model, we introduce a novel method that employs foundation models to generate highly accurate object-level masks and semantic text information at the object level. Our approach notably outshines state-of-the-art methods in 3D object detection and semantic segmentation tasks. For instance, on the ScanNet dataset, our method surpasses the previous state-of-the-art method, PiMAE, by a significant margin of 5.3%.

# Summary. An optional shortened abstract.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://arxiv.org/pdf/2305.08776.pdf
url_code: 'https://github.com/Zhimin-C/Bridge3D'
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'

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

