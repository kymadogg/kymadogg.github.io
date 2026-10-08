---
title: "Welcome!"
layout: splash
permalink: /
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/otto_evolution.png
#   actions:
#     - label: "Download"
#       url: "https://github.com/mmistakes/minimal-mistakes/"
  # caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "My attention span is short and list of technical intrests long"
intro: 
  - excerpt: 'Robotics Software Developer'
feature_row:
  - image_path: assets/images/ros_logo_3.png
    alt: "ROS 2 dots"
    title: "ROS 2"
    excerpt: "`rclpy`, `rclcpp`, ROS 2 Control, Navigation2, and other popular packages + frameworks."
  - image_path: /assets/images/gazebo.png
    #image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Gazebo Sim"
    excerpt: "Building simulation worlds using SDF. Making them interactive using ROS"
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--primary"
  # - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
  #   title: "Placeholder 3"
  #   excerpt: "This is some sample content that goes here with **Markdown** formatting."
# feature_row2:
#   - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Left Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
#     url: "#test-link"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
# feature_row3:
#   - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Right Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
#     url: "#test-link"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
# feature_row4:
#   - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Center Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
#     url: "#test-link"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

<!-- <div>
  {{ site.posts.first.content }}
</div> -->
<h3>My latest post: <a href="{{ site.posts.first.url }}">{{ site.posts.first.title }}</a></h3>

<h2>Technical Skills</h2>

{% include feature_row %}

<!-- {% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %} -->