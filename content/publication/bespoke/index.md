---
title: 'Bespoke: A Block-Level Neural Network Optimization Framework for Low-Cost Deployment'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yong-Hyuk Moon

date: '2023-06-26'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-06-26'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the AAAI Conference on Artificial Intelligence
publication_short: In *AAAI 2023*

abstract: As deep learning models become popular, there is a lot of need for deploying them to diverse device environments. Because it is costly to develop and optimize a neural network for every single environment, there is a line of research to search neural networks for multiple target environments efficiently. However, existing works for such a situation still suffer from requiring many GPUs and expensive costs. Motivated by this, we propose a novel neural network optimization framework named Bespoke for low-cost deployment. Our framework searches for a lightweight model by replacing parts of an original model with randomly selected alternatives, each of which comes from a pretrained neural network or the original model. In the practical sense, Bespoke has two significant merits. One is that it requires near zero cost for designing the search space of neural networks. The other merit is that it exploits the sub-networks of public pretrained neural networks, so the total cost is minimal compared to the existing works. We conduct experiments exploring Bespoke's the merits, and the results show that it finds efficient models for multiple targets with meager cost.

# Summary. An optional shortened abstract.
summary: This paper proposed a framework for compressing neural network models with consideration of their target platform.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ojs.aaai.org/index.php/AAAI/article/view/26020/25792'
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
