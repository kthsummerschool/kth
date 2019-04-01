---
layout: splash
author_profile: true
excerpt: " Game technologies
<br>
 Character animation and perception
<br>
 Mobile and multi-agent systems
<br>
 Virtual and augmented reality
<br>
 Project design and prototyping
<br>
+ blog and presentation, ethics, gender"

header:
  overlay_image: /assets/images/kth_banner.png
  overlay_filter: rgba(255, 0, 0, 0.5)
  caption: "KTH - Royal Institute of technology - (https://www.kth.se/en)"
  actions:
  #  - label: "More Info"
      url: "https://www.kth.se/en"

intro: 
  - excerpt: 'WHEN: 20/05/2019 To 24/05/2019 <br> WHERE: KTH - Royal Institute of technology, Stockholm, Sweden'
feature_row:
  - image_path: assets/images/KTHLogo.png
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/KTHLogo.png
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/KTHLogo.png
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/KTHLogo.png
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/KTHLogo.png
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/KTHLogo.png
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
