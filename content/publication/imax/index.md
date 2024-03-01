
---
title: 'A Query Approach for Influence Maximization on Specific Users in Social Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Chin-Wan Chung

date: '2015-02-01'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2015-02-01'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-journal']

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Knowledge and Data Engineering
publication_short: In *IEEE TKDE*

abstract: Influence maximization is introduced to maximize the profit of viral marketing in social networks. The weakness of influence maximization is that it does not distinguish specific users from others, even if some items can be only useful for the specific users. For such items, it is a better strategy to focus on maximizing the influence on the specific users. In this paper, we formulate an influence maximization problem as query processing to distinguish specific users from others. We show that the query processing problem is NP-hard and its objective function is submodular. We propose an expectation model for the value of the objective function and a fast greedy-based approximation method using the expectation model. For the expectation model, we investigate a relationship of paths between users. For the greedy method, we work out an efficient incremental updating of the marginal gain to our objective function. We conduct experiments to evaluate the proposed method with real-life datasets, and compare the results with those of existing methods that are adapted to the problem. From our experimental results, the proposed method is at least an order of magnitude faster than the existing methods in most cases while achieving high accuracy.

# Summary. An optional shortened abstract.
summary: This paper proposed a IMAX query, which is a new type of queries for making influences on specfic target users, and an efficient method to answer it.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.academia.edu/download/81677762/imq.pdf'
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
