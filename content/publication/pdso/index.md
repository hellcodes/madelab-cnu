---
title: 'Efficient Distance Sensitivity Oracles for Real-World Graph Data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Chin-Wan Chung

date: '2021-01-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-01-01'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-journal']

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Knowledge and Data Engineering
publication_short: In *IEEE TKDE*

abstract: A distance sensitivity oracle is a data structure answering queries that ask the shortest distance from a node to another in a network expecting node/edge failures. It has been mainly studied in theory literature, but all the existing oracles for a directed graph suffer from prohibitive preprocessing time and space. Motivated by this, we develop two practical distance sensitivity oracles for directed graphs as variants of Transit Node Routing. The first oracle consists of a novel fault-tolerant index structure, which is used to construct a solution path and to detect and localize the impact of network failures, and an efficient query algorithm for it. The second oracle is made by applying the A* heuristics to the first oracle, which exploits lower bound distances to effectively reduce search space. In addition, we propose additional speed-up techniques to make our oracles faster with a slight loss of accuracy. We conduct extensive experiments with real-life datasets, which demonstrate that our oracles greatly outperform all of competitors in most cases. To the best of our knowledge, our oracles are the first distance sensitivity oracles that handle real-world graph data with million-level nodes.

# Summary. An optional shortened abstract.
summary: This paper dealt with efficient methods for answering distance queries with expecting some edge failures.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'http://islab.kaist.ac.kr/chungcw/interJournal_papers/tkde%202021.pdf'
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
