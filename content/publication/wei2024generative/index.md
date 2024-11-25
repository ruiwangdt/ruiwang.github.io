---
title: 'Generative PDE Control'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Long Wei
  - Peiyan Hu
  - Ruiqi Feng
  - Yixuan Du
  - Tao Zhang
  - admin
  - Yue Wang
  - Zhi-Ming Ma
  - Tailin Wu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-03-01T00:00:00Z'
# doi: '10.1007/978-3-031-43421-1_4'

# Schedule page publish date (NOT publication's date).
# publishDate: '2024-11-24T12:10:05.844670Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: ICLR 2024 Workshop on AI4DifferentialEquations In Science
publication_short: ICLR 2024 Workshop AI4DiffEqtnsInSci

abstract: Controlling PDE is a fundamental task across science and engineering. Classical techniques for PDE control tend to be computationally demanding and recent deep learning-based approaches often struggle to optimize long-term control sequences. In this work, we introduce Diffusion generative PDE Control (DiffConPDE), a new class of method to address the PDE control problem. DiffConPDE excels by simultaneously minimizing both the learned generative energy function and the predefined control objectives across the entire trajectory and control sequence. Moreover, we enhance DiffConPDE with prior reweighting, enabling the discovery of control sequences that significantly deviate from the training distribution. We test our method in 2D jellyfish movement in a fluid environment and 1D Burgers' equation control. Our method consistently outperforms baselines. Notably, DiffConPDE unveils an intriguing fast-close-slow-open pattern observed in the jellyfish, aligning with established findings in the field of fluid dynamics.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://aclanthology.org/2023.acl-long.354/

# url_pdf: content/publication/wei2024generative/Generative_PDE_Control.pdf
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
