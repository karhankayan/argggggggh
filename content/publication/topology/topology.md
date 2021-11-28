---
title: "Topology Layers for cGANs and DCGANs"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
#author_notes:

date: "2021-03-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
#publication: In *Wowchemy Conference*
#publication_short: In *ICW*

abstract: Recently, it has been shown that it is possible to incorporate topological priors into Generative Adversarial Networks (GAN) using persistent homology and topological loss functions. Given accurate topological priors about the input distribution, generative models can converge to the population distribution much more rapidly by minimizing the topological noise. In this paper, we show that it is possible to apply this approach to Deep Convolutional GANs (DCGAN) and conditional GANs (cGAN). Empirical evidence in both architectures show that topological layers reduce the noise in the generated images to a significant degree. Furthermore, integrating these layers into conditional GANs makes it possible to promote different priors for different kinds of images in the dataset, which is not possible using GANs. Experimentally, we show that it is possible to get mild improvements over the original topology layer approach (using the same layer for every kind of image). We further test the topological layers in colored images with 3 color channels, and show that even though they do not improve the image quality, they might be of potential use in semantic segmentation tasks in the future.  

# Summary. An optional shortened abstract.
summary: The final project for my Topological Data Analysis course. The idea is based on <a href="http://proceedings.mlr.press/v108/gabrielsson20a.html">this paper</a> that shows that the noise in GAN generated images can be reduced by introducing a topology layer. I show that this layer can also be integrated into cGANs and DCGANs and give better results on cGANs due to the possibility of specific loss functions. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '/publication/topology/Final_Project.pdf'
url_code: 'https://github.com/karhankayan/TopLayer'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
