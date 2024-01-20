---
title: "NightRain: Nighttime Video Deraining via Adaptive-Rain-Removal and Adaptive-Correction"
summary: An example of using the in-built project page.
tags:
  - 'Image and Video Enhancement'
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Existing deep-learning-based methods for nighttime video deraining rely on synthetic data due to the absence of real-world paired data. However, the intricacies of the real world, particularly with the presence of light effects and low-light regions affected by noise, create significant domain gaps, hampering synthetic-trained models in removing rain streaks properly and leading to over-saturation and color shifts. Motivated by this, we introduce NightRain, a novel nighttime video deraining method with adaptive-rain-removal and adaptive-correction. Our adaptive-rain-removal uses unlabeled rain videos to enable our model to derain real-world rain videos, particularly in regions affected by complex light effects. The idea is to allow our model to obtain rain-free regions based on the confidence scores. Once rain-free regions and the corresponding regions from our input are obtained, we can have region-based paired real data. These paired data are used to train our model using a teacher-student framework, allowing the model to iteratively learn from less challenging regions to more challenging regions. Our adaptive-correction aims to rectify errors in our model's predictions, such as over-saturation and color shifts. The idea is to learn from clear night input training videos based on the differences or distance between those input videos and their corresponding predictions. Our model learns from these differences, compelling our model to correct the errors. From extensive experiments, our method demonstrates state-of-the-art performance. It achieves a PSNR of 26.73dB, surpassing existing nighttime video deraining methods by a substantial margin of 13.7%.