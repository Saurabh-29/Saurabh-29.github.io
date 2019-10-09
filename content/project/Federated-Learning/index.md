---
title: Federated Learning
summary: 'FADMM: A faster approach to federated optimization'
tags:
- Deep Learning
date: "2017-07-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Federated Learning Setup
  focal_point: Smart

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.

---

The project solved the problem of L1 regularized regression task to reduce latency under different communication protocols when data is distributed across multiple heterogeneous devices i.e. in Federated Setting. Data is distributed across devices, with no central copy, model is trained on edge devices and parameters are shared across different devices through servers. Different compute capability, network capability and asynchronous nature make the problem challenging. We proposed **FADMM: A faster approach to federated optimization** which achieved faster convergence than baselines. You can find the detailed report [here](https://docs.google.com/document/d/160m1Udb0F0XXdvRwF-kjr9d6KSmkjjc0nTSte7gdddE/edit?usp=sharing)