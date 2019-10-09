---
title: Speech Synthesis
summary: Speech Synthesis for Indian Laguages
tags:
- Deep Learning
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart


# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
I have been working on this project for last 1 year. This project dealt with the problem of automated Speech Synthesis for Indian Languages that resembles, as closely as possible, a native speaker of the language. I was involved end-to-end in this project. It comprised of various steps such as:


1) **Data Collection**- Collection data from various sources such as audio-books, studio recording. We also used some open-source datasets like LjSpeech, VCTK etc.

2) **Data Cleaning**- Cleaning data to get the non-noisy audio-text aligned pairs

3) **Training Models**- It involved working on models like Tacotron, Voiceloop for text to mel systems and working on models for Wavenet, Parellel Wavenet, Clarinet and Waveglow for mel to speech systems. 

4) **CUDA Inference**- Write the CUDA inference of models for faster inference.

The project also involved working on some sub-projects to improve the overall MOS(Mean Opinion Score) such as:

1) **Prosody Transfer**-  For making the speech more prosodic(natural)

2) **Multi-Speaker TTS**-  To add multi-speaker support in our model

3) **Speaker-Separation**-  For separating dominant speakers from other spakers, used in data collection