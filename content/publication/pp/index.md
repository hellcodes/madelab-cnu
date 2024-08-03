---
title: 'Rethinking Group Fisher Pruning for Efficient Label-Free Network Compression'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yong-Hyuk Moon

date: '2022-11-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-11-01'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In the British Machine Vision Conference (BMVC)
publication_short: In <b>*BMVC 2023*</b>

abstract: Group Fisher Pruning is a powerful gradient-based channel pruning method for convolutional neural networks. Even though it provides excellent convenience for allocating sparsity over layers with strong effectiveness, the cost of its pruning process is significantly expensive for large neural networks. In addition, it was proposed to handle neural networks having residual connections, but it still cannot handle concatenation-type connections like DenseNet. These drawbacks make Group Fisher Pruning hard to be utilized for somewhat large or complex neural networks. Motivated by them, we propose an improved method based on Group Fisher Pruning for efficiency and applicability. For efficiency, we parameterize the number of pruned channels at each pruning step and demonstrate that it can be a much larger value than one. We devise a formal algorithm for applicability to prune DenseNet-style neural networks. In addition, we devise a knowledge distillation-based channel importance scoring scheme that can work for label-free channel pruning, which is a crucial task for exploiting unlabeled data from edge devices. To demonstrate the superiority of our method, we conduct extensive experiments dealing with label-free channel pruning. Our method prunes neural networks at most two orders of magnitude faster than Group Fisher Pruning with comparable accuracy. It should be noticed that our method does not require any label for pruning and retraining while Group Fisher Pruning does.

# Summary. An optional shortened abstract.
summary: This paper proposed an efficient channel pruning without labels based on Group Fisher Pruning.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://bmvc2022.mpi-inf.mpg.de/0693.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: []
---
