---
title: 'Block-wise Word Embedding Compression Revisited: Better Weighting and Structuring'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yong-Ju Lee
  - Yong-Hyuk Moon

date: '2021-11-07'
doi: '10.18653/v1/2021.findings-emnlp.372'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-11-07'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "In Findings of the Association for Computational Linguistics: EMNLP 2021"
publication_short: In *EMNLP(Findings) 2021*

abstract: Word embedding is essential for neural network models for various natural language processing tasks. Since the word embedding usually has a considerable size, in order to deploy a neural network model having it on edge devices, it should be effectively compressed. There was a study for proposing a block-wise low-rank approximation method for word embedding, called GroupReduce. Even if their structure is effective, the properties behind the concept of the block-wise word embedding compression were not sufficiently explored. Motivated by this, we improve GroupReduce in terms of word weighting and structuring. For word weighting, we propose a simple yet effective method inspired by the term frequency-inverse document frequency method and a novel differentiable method. Based on them, we construct a discriminative word embedding compression algorithm. In the experiments, we demonstrate that the proposed algorithm more effectively finds word weights than competitors in most cases. In addition, we show that the proposed algorithm can act like a framework through successful cooperation with quantization.

# Summary. An optional shortened abstract.
summary: This paper proposed a compression method for word embedding based on block-wise low-rank compression.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2021.findings-emnlp.372.pdf'
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
