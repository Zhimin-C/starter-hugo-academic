---
title: 'Class-Level Confidence Based 3D Semi-Supervised Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Longlong Jing
  - Liang Yang
  - Yingwei Li
  - Bing Li


date: '2022-10-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)
publication_short: In *WACV, 2023*

abstract: Current pseudo-labeling strategies in 3D semi-supervised learning (SSL) fail to dynamically incorporate the variance of learning status which is affected by each class's learning difficulty and data imbalance. To address this problem, we practically demonstrate that 3D unlabeled data class-level confidence can represent the learning status. Based on this finding, we present a novel class-level confidence based 3D SSL method. Firstly, a dynamic thresholding strategy is proposed to utilize more unlabeled data, especially for low learning status classes. Then, a re-sampling strategy is designed to avoid biasing toward high learning status classes, which dynamically changes the sampling probability of each class. Unlike the latest state-of-the-art SSL method FlexMatch which also utilizes dynamic threshold, our method can be applied to the inherently imbalanced dataset and thus is more general. To show the effectiveness of our method in 3D SSL tasks, we conduct extensive experiments on 3D SSL classification and detection tasks. Our method significantly outperforms state-of-the-art counterparts for both 3D SSL classification and detection tasks in all datasets.

# Summary. An optional shortened abstract.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://openaccess.thecvf.com/content/WACV2023/papers/Chen_Class-Level_Confidence_Based_3D_Semi-Supervised_Learning_WACV_2023_paper.pdf
url_code: 'https://github.com/AutoAILab/Confid-SSL'

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

