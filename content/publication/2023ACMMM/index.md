---
title: 'Enhancing Visibility in Nighttime Haze Images Using Guided APSF and Gradient Adaptive Convolution'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Yeying Jin
- Beibei Lin
- Wending Yan
- Yuan Yuan
- Wei Ye
- Robby Tan


# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-10-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: ACM Multimedia 2023
publication_short: In *ACM MM 23*

abstract: Visibility in hazy nighttime scenes is frequently reduced by multiple factors, including low light, intense glow, light scattering, and the presence of multicolored light sources. Existing nighttime dehazing methods often struggle with handling glow or low-light conditions, resulting in either excessively dark visuals or unsuppressed glow outputs. In this paper, we enhance the visibility from a single night- time haze image by suppressing glow and enhancing low-light regions. To handle glow effects, our framework learns from the rendered glow pairs. Specifically, a light source aware network is proposed to detect light sources of night images, followed by the APSF (Angular Point Spread Function)-guided glow rendering. Our framework is then trained on the rendered images, resulting in glow suppression. Moreover, we utilize gradient-adaptive convolution, to capture edges and textures in hazy scenes. By leveraging extracted edges and textures, we enhance the contrast of the scene without losing important structural details. To boost low-light intensity, our network learns an attention map, then adjusted by gamma correction. This attention has high values on low-light regions and low values on haze and glow regions. Extensive evaluation on real nighttime haze images, demonstrates the effectiveness of our method. Our experiments demonstrate that our method achieves a PSNR of 30.38dB, outperforming state-of-the-art methods by 13% on GTA5 nighttime haze dataset. Our data and code is available at [GitHub](https://github.com/jinyeying/nighttime_dehaze).


# Summary. An optional shortened abstract.
summary: ACM Multimedia (ACM MM) 2023

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2308.01738'
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
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
