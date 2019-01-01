---
title: "Poetry"
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/kaqchikel2.jpg
  caption: "I am a poet."
intro: 
  - excerpt: I am a poet'
feature_row:
  - image_path: assets/images/authorphoto.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "Entrevista a Ignacio Carvajal por Xánath Caraza."
    url: "https://revistaliterariamonolito.com/entrevista-a-ignacio-carvajal-por-xanath-caraza/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: kaqchikel2.jpg
    image_caption: "placeholder image 2"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: kaqchikel2.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: kaqchikel2.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: kaqchikel2.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}