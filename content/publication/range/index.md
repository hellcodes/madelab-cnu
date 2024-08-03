---
title: 'Range Aggregation With Set Selection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yufei Tao
  - Cheng Sheng
  - Chin-Wan Chung
  - admin

date: '2013-07-29'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2013-07-29'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-journal']

# Publication name and optional abbreviated publication name.
publication: "In IEEE Transactions on Knowledge and Data Engineering"
publication_short: In *IEEE TKDE*

abstract: In the classic range aggregation problem, we have a set S of objects such that, given an interval I, a query counts how many objects of S are covered by I. Besides COUNT, the problem can also be defined with other aggregate functions, e.g., SUM, MIN, MAX and AVERAGE. This paper studies a novel variant of range aggregation, where an object can belong to multiple sets. A query (at runtime) picks any two sets, and aggregates on their intersection. More formally, let S 1 ,...,S m be m sets of objects. Given distinct set ids i, j and an interval I, a query reports how many objects in S i ∩ S j are covered by I. We call this problem range aggregation with set selection (RASS). Its hardness lies in that the pair (i, j) can have ( 2 m ) choices, rendering effective indexing a non-trivial task. 2 The RASS problem can also be defined with other aggregate functions, and generalized so that a query chooses more than 2 sets. We develop a system called RASS to power this type of queries. Our system has excellent efficiency in both theory and practice. Theoretically, it consumes linear space, and achieves nearly-optimal query time. Practically, it outperforms existing solutions on real datasets by a factor up to an order of magnitude. The paper also features a rigorous theoretical analysis on the hardness of the RASS problem, which reveals invaluable insight into its characteristics.

# Summary. An optional shortened abstract.
summary: This paper dealt with an efficient index structure to answer range queries with set selection constraints.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/6570726'
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
