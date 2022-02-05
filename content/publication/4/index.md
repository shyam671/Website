---
title: "ORDER: Open World Object Detection on Road Scenes (NurIPSw 2021)"
authors:
- Shyam Nandan Rai*
- Deepak Kumar Singh*
- K J Joseph
- Rohit Saluja
- Vineeth N Balasubramanian
- Chetan Arora
- Anbumani Subramanian
- C. V. Jawahar
#date: "NurIPSw 2021"
#doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: NurIPSw 2020
publication_short: In *STC*

abstract: Object detection is a key component in autonomous navigation systems that enables localization and classification of the objects in a road scene. Existing object detection methods are trained and inferred on a fixed number of known classes present in road scenes. However, in real-world or open-world road scenes, while inference, we come across unknown objects that the detection model hasn’t seen while training. Hence, we propose Open World Object Detection on Road Scenes (ORDER) to address the aforementioned problem for road scenes. Firstly, we introduce Feature-Mix to improve the unknown object detection capabilities of an object detector. Feature-Mix widens the gap between known and unknown classes in latent feature space that helps improve the unknown object detection. Next, we identify that the road scene dataset compared to generic object dataset contains a significant proportion of small objects and has higher intra-class bounding box scale variations, making it challenging to detect the known and unknown objects. We propose a novel loss: Focal regression loss that collectively addresses the problem of small object detection and intra-class bounding box by penalizing more the small bounding boxes and dynamically changing the loss according to object size. Further, the detection of small objects is improved by curriculum learning. Finally, we present an extensive evaluation on two road scene datasets: BDD and IDD. Our experimental evaluations on BDD and IDD shows consistent improvement over the current state-of-the-art method. We believe that this work will lay the foundation for real-world object detection for road scenes.

# Summary. An optional shortened abstract.
summary:  
tags:
- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://ml4ad.github.io/files/papers2021/ORDER:%20Open%20World%20Object%20Detection%20on%20Road%20Scenes.pdf
#url_code: 'https://github.com/shyam671/Spatial-Feedback-Learning-to-ImproveSemantic-Segmentation-in-Hot-Weather'
#url_project: ''
#url_dataset: '#'
#url_poster: '#'
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}
