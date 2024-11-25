---
title: 'Distributed learning for uplink cell-free massive MIMO networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Weijie Dai
  - Yi Jiang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-06-22T00:00:00Z'
doi: '10.1109/TCOMM.2023.3288578'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-06-22T12:10:05.844670Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['paper-conference']
publication_types: ["article-journal"]
# publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Communications
publication_short: IEEE TCOMM

abstract: Cell-free massive multiple-input multiple-output (MIMO) can resolve the inter-cell interference issue in cellular networks through cooperative beamforming of the distributed access points (APs). This paper focuses on an uplink cell-free massive MIMO network and investigates novel methods to train the central processing unit (CPU), the APs, and the users in the network. To reduce the communication burden posed on the fronthaul, each AP applies receive beamforming to compress the vector signals into scalar ones before passing them to the CPU for centralized processing. By drawing analogies between an uplink cell-free network and a quasi-neural network and borrowing the idea of backpropagation algorithm, we propose a novel scheme named the distributed learning for uplink cell-free massive MIMO beamforming (DLCB), which can achieve the multi-AP cooperation without explicit estimation of their channel state information (CSI). The DLCB has low computational complexity and is applicable to various objective functions, such as the minimum mean squared error criterion and the maximum sum rate criterion. Extensive simulations verify that the proposed scheme achieves superior performance over the state-of-the-art methods.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://aclanthology.org/2023.acl-long.354/

url_pdf: content/publication/wang2023distributed/Distributed_Learning_for_Uplink.pdf
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
