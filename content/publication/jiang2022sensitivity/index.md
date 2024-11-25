---
title: 'Sensitivity of bluetooth receiver by introducing interleaver'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yi Jiang
  - Jie Yang
  - Qinghe Du
  - admin
  - Wei Zhang
  - Li Fengjie

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-09-27T00:00:00Z'
doi: 'US11456818B2'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-09-27T12:10:05.844670Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['paper-conference']
# publication_types: ["article-journal"]
publication_types: ["patent"]

# Publication name and optional abbreviated publication name.
publication: Patent
# publication_short: ITA Workshop

abstract: The invention belongs to the field of low-power consumption Bluetooth technology in wireless communication, in particular to a method for improving the sensitivity of the receiver in a low-power consumption Bluetooth system. The method of the invention is to introduce a deinterleaver between the symbol pattern mapper and GFSK modulator of the transmitting terminal under the low-power consumption Bluetooth coding mode, which is used to perform additional processing on the bitstream data and then perform modulation; then, due to the introduction of interleaving, Turbo iterative processing of demodulation and decoding can be performed at the receiving terminal; the receiving terminal comprises a Turbo iterative demodulator and decoder, which is used to model the low-power consumption Bluetooth GFSK modulator and convolutional coder into finite state machines, and then combine the deinterleaver to use the BCJR algorithm for iterative demodulation and decoding.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://aclanthology.org/2023.acl-long.354/

url_pdf: 'https://patents.google.com/patent/US11456818B2/en'
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
