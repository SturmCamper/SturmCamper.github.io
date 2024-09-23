---
title: "Welcome to my Site"
layout: splash
permalink: /
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/overlay_landing_page_5.png
  actions:
    - label: "Download my CV"
      url: "https://github.com/SturmCamper/SturmCamper.github.io/tree/master/assets/CV/Patrick_CV.pdf"
  caption: "Photo credit: [**Stable Diffusion**](https://stability.ai/)"
excerpt: "I am Patrick. Here, you will find my portfolio, projects, publication and contact information."
intro: 
  - excerpt: "Hello visitor, my name ist Patrick. I am currently pursuing a master's in medical informatics with a strong passion for technology. My hobbies include tinkering, sports, and I have a keen interest in AI and software development. I love sports, particularly bouldering and volleyball."
feature_row1:
  - image_path: /assets/images/skills.jpg
    alt: "placeholder image 2"
    title: "Skills"
    url: "/personal/Skills/"
    btn_label: "Discover Me"
    btn_class: "btn--primary"
    excerpt: >
      I have a diverse skill set, ranging from full-stack software development and networking to experience with machine learning in the field neuroscience. <br>
      <br>
      Experince with: <i class="fa-brands fa-docker"></i> <i class="fa-brands fa-java"></i> <i class="fa-brands fa-python"></i> <i class="fa-brands fa-aws"></i> <i class="fa-brands fa-github"></i> ...
feature_row2:
  - image_path: /assets/images/work.png
    alt: "placeholder image 2"
    title: "Work Experiences"
    excerpt: "I'm currently working as a part-time academic worker at Hochschule Heilbronn. Previously, I worked as a working student in the Testing Department."
    url: "/personal/Work/"
    btn_label: "For More Information"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/books.png
    alt: "Publications"
    title: "Publications"
    excerpt: 'My latest publication, titled "A Web Application for the Interactive Visualization of the German Health Web," was published for the GMDS 2022.'
    url: "#test-link"
    btn_label: "For More Information"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row1" type="left" %}

{% include feature_row id="feature_row2" type="right" %}

{% include feature_row id="feature_row3" type="left" %}