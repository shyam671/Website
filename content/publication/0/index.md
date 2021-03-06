---
title: "Munich-to-Dubai: How far is it for Semantic Segmentation ? (WACV 2020)"
authors:
- admin
- Vineeth N Balasubramanian
- Anbumani Subramanian
- C. V. Jawahar
#date: "WACV 2020"
#doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: WACV 2020
publication_short: In *STC*

abstract: Cities having hot weather conditions results in geometrical distortion, thereby adversely affecting the performance of semantic segmentation model. In this work, we study the problem of semantic segmentation model in adapting to such hot climate cities. This issue can be circumvented by collecting and annotating images in such weather conditions and training segmentation models on those images. But the task of semantically annotating images for every environment is painstaking and expensive. Hence, we propose a framework that improves the performance of semantic segmentation models without explicitly creating an annotated dataset for such adverse weather variations. Our framework consists of two parts, a restoration network to remove the geometrical distortions caused by hot weather and an adaptive segmentation network that is trained on an additional loss to adapt to the statistics of the ground-truth segmentation map. We train our framework on the Cityscapes dataset, which showed a total IoU gain of 12.707 over standard segmentation models. We also observe that the segmentation results obtained by our framework gave a significant improvement for small classes such as poles, person, and rider, which are essential and valuable for autonomous navigation based applications.

# Summary. An optional shortened abstract.
summary:  Cities having hot weather conditions results in geometrical distortion, thereby adversely affecting the performance of semantic segmentation model. In this work, we study the problem of semantic segmentation model in adapting to such hot climate cities.

tags:
- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: http://cdn.iiit.ac.in/cdn/cvit.iiit.ac.in/images/ConferencePapers/2020/Munich2Dubai-wacv.pdf
url_code: 'https://github.com/shyam671/Munich-to-Dubai-How-far-is-it-for-Semantic-Segmentation'
url_project: 'http://cvit.iiit.ac.in/research/projects/cvit-projects/vision-in-atmospheric-turbulence'
#url_dataset: '#'
#url_poster: '#'
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'We show the performance of various semantic segmentation methods on a turbulent (hot weather condition) image. Our method clearly outperforms DeepLabV3 and Coral-DLV3 (DeepLabV3 trained on CORAL loss). We can notice that our approach removes the noisy segmentation output (can be seen on the segmentation output of roads) of Coral-DLV3 giving higher IoU and refined segmentation output.'
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
