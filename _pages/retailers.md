---
layout: single
read_time: false
comments: false
share: false
title: Research Highlights
permalink: /research/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/trinity.jpg
  caption: "Photo: [Olly McMillan](https://www.youtube.com/watch?v=kQkZeXHfgwA&t=1s)"
excerpt: "Geometry and Uncertainty in Deep Learning for Computer Vision<br><br><br>"
gallery_uncertainty:
  - image_path: /assets/images/research/input.png
    alt: "Input Image"
  - image_path: /assets/images/research/segmentation.png
    alt: "Semantic Segmentation"
  - image_path: /assets/images/research/uncertainty.jpg
    alt: "Uncertainty"
---

I am excited about research which advances the perception and control of mobile robotics.
In particular, I am currently working on leveraging geometry for unsupervised learning, reasoning under uncertainty with Bayesian deep learning and developing end-to-end systems which can reason from perception to control. 
My research has been used to power smart-city infrastructure with [Vivacity](http://www.vivacitylabs.com/), control self-driving cars with [Toyota Research Institute](http://www.tri.global/) and enable next-generation drone flight with [Skydio](https://www.skydio.com/).

# Scene Understanding


| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

Scene understanding is a fundamental task in computer vision which requires understanding the scene's geometry and semantic structure.
Initially, I worked on a semantic segmentation algorithm called [SegNet](http://mi.eng.cam.ac.uk/projects/segnet/).
More recently, I have been interested in learning depth, instance and semantic segmentation from a [unified deep learning architecture](https://arxiv.org/pdf/1705.07115.pdf).

![image-center]({{ site.url }}{{ site.baseurl }}/assets/images/multitask.jpg){: .align-center}

---

# Bayesian Deep Learning

Deep learning is great for achieving state-of-the-art results, however these models cannot understand what they don't know.
Bayesian deep learning (BDL) is a very exciting framework for understanding our model's uncertainty.
[This paper](https://arxiv.org/pdf/1703.04977.pdf) is an introduction to Bayesian deep learning for computer vision. 
I have also found BDL useful for [localisation](http://arxiv.org/abs/1509.05909) and [scene understanding](http://arxiv.org/abs/1511.02680).

{% include gallery id="gallery_uncertainty" caption="Bayesian deep learning for semantic segmentation. From left to right: input image, semantic segmentation and model uncertainty." %}

---

# Localisation

[PoseNet](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Kendall_PoseNet_A_Convolutional_ICCV_2015_paper.pdf) is an algorithm for relocalisation - 
estimating the position and orientation of the camera from an image within a previously explored area. 
It works over large outdoor urban environments or inside buildings. 
It takes only 5ms to do this from a single colour image, [here is a demo](http://mi.eng.cam.ac.uk/projects/relocalisation/).

Check out some 3D reconstructions of [King's College](http://mi.eng.cam.ac.uk/~agk34/map.html) and [central Cambridge](http://mi.eng.cam.ac.uk/~agk34/viewer.html) in your web browser.

![image-center]({{ site.url }}{{ site.baseurl }}/assets/images/research/localisation.jpg){: .align-center}

---

# Other Projects

Some more details of other projects, including an autonomous drone and augmented reality, [can be found here](/other_projects/).
