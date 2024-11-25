---
title: 'Joint estimation of velocity, angle-of-arrival and range (JEVAR) using a conjugate pair of Zadoff-Chu sequences'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhiyu Yang
  - admin
  - Yi Jiang
  - Jian Li

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2021-10-27T00:00:00Z'
doi: '10.1109/TSP.2021.3122907'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-10-27T12:10:05.844670Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['paper-conference']
publication_types: ["article-journal"]
# publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Signal Processing
publication_short: IEEE TSP

abstract: This paper studies the joint estimation of velocity, AOA, and range (JEVAR) of a target in a multipath environment, which has gain renewed interest with the advent of 5G Internet of Things (IoT) technologies, owing to the numerous emerging localization-related applications. To solve the JEVAR problem, we propose a novel scheme, wherein the target transmits a pair of conjugate Zadoff-Chu (ZC) sequences and the multi-antenna receiver conducts maximum likelihood (ML) estimation. The proposed scheme is computationally efficient it uses alternating projection (AP) to reduce the high-dimensional problem due to the multipaths to multiple lower-dimensional ones per path; it uses a conjugate pair of ZC sequences to decouple the joint estimation of the frequency and time offsets of each path into two separate estimates. The proposed scheme is highly versatile it can resolve the multipaths with super resolution in both spatial and temporal domain; it can measure the velocity of the target via estimating the frequency offsets of the line-of-sight (LOS) signal and its multipath reflections. The simulations verify the effectiveness of the proposed scheme by showing that its performance can approach the Cramer-Rao bound (CRB).

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://aclanthology.org/2023.acl-long.354/

url_pdf: content/publication/yang2021joint/Joint_Estimation_of_Velocity.pdf
# url_code: 'https://github.com/Hytn/AspectSum'
# url_dataset: 'https://github.com/Hytn/DocRED-HWE'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://aclanthology.org/2023.acl-long.354.mp4'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
# slides: example
---
