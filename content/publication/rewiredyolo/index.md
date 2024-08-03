---
title: 'Revisiting Layer-level Residual Connections for Efficient Object Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yong-Hyuk Moon

date: '2024-07-14'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-14'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In AVSS 2024
publication_short: In <b>*AVSS 2024*</b>

abstract: "Modern neural network models commonly have residual connections, because they are helpful to achieve better performance. Due to their unconditional popularity, modifying them to achieve a better efficiency-accuracy trade-off is rarely studied in the literature. Motivated by this, we study how to get an efficient sub-network by rewiring a neural block having residual connections based on their inference paths. Based on this, we devise a new simulated annealing-based neural network rewiring method. Then, we construct a simple yet effective compression pipeline by combining this rewiring method and a recent channel pruning method. To demonstrate the effectiveness of the pipeline, we use object detection as the target task and consider YOLOv8 as the target model. We conduct experiments with two well-known datasets: VisDrone and PASCAL VOC. The results of the experiments demonstrate that our pipeline successfully outperforms the pruning method alone in most cases. Compared to YOLOv8 series, our method can offer more accurate models for VisDrone."

# Summary. An optional shortened abstract.
summary: This paper proposed a rewiring scheme for effectively compressing YOLOv8.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
