---
layout: single
title:  Image Caption Generation with Attention Mechanism
date:   2023-03-12 10:00:00 +0800
permalink: /image-caption-generator/
excerpt: Capstone project from Data Science Immersive. Trained an image caption generator with attention mechanism that achieved a BLEU-1 score of 0.52 on the Flickr30k dataset.
tags: python tensorflow keras computer-vision natural-language-processing 
---

As part of my 12-week Data Science Immersive program, I completed a Capstone project focused on building an image caption generator using a transformer architecture in TensorFlow and Keras. The model trained on the Flickr30k dataset achieved a BLEU-1 score of 0.52 and has been deployed on Streamlit, allowing users to upload their own images and generate captions.

There are various real-world applications for image captioning. Visually impaired individuals can better understand the content of images through generated captions and thus improve their overall accessibility to information. Such models could also be trained to analyse and interpret X-rays in healthcare, helping medical professionals more efficiently diagnose and treat patients.

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://eeshawn-dsi-capstone.streamlit.app/)

**Skills Demonstrated:**

- Deep learning, computer vision and natural language processing with `TensorFlow` and `Keras`
- Handling of large dataset using TensorFlow's tf.data API
- Deployment of custom Keras model to `streamlit` web app