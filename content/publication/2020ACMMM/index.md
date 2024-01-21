---
title: 'Gait Recognition with Multiple-Temporal-Scale 3D Convolutional Neural Network'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Beibei Lin
- Shunli Zhang
- Feng Bao


# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2020-10-12T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-10-12T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: ACM Multimedia 2020
publication_short: In *ACM MM 20*

abstract: Gait recognition which is one of the most important and effective biometric technologies has a significant advantage in long-distance recognition systems. For existing gait recognition methods, the template-based approaches may lose temporal information, while the sequence-based methods cannot fully exploit the temporal relations among the sequence. To address the above issues, we propose a novel multiple-temporal-scale gait recognition framework which integrates the temporal information in multiple temporal scales, making use of both the frame and interval fusion information. Moreover, the interval-level representation is realized by a local transformation module. Concretely, 3D convolution neural network (3D CNN) is applied in both the small and the large temporal scales to extract the spatial-temporal information. Moreover, a frame pooling method is developed to address the mismatch of the input of 3D network and video frames, and a novel 3D basic network block is designed to improve efficiency. Experiments demonstrate that the multiple-temporal-scale 3D CNN based gait recognition method can achieve better performance than most recent state-of-the-art methods in CASIA-B dataset. The proposed method obtains the rank-1 accuracy with 96.7% under normal condition, and outperforms other methods on average accuracy by at least 5.8% and 11.1%, respectively, in complex scenarios.


# Summary. An optional shortened abstract.
summary: ACM Multimedia (ACM MM) 2023

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3394171.3413861'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

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

# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.

#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
