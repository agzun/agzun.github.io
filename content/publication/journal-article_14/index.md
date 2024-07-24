---
title: "Lost in the Deep?: Performance Evaluation of Dead Reckoning Techniques in Underwater Environments"
authors:
- Marko Radeta
- Claudio Rodrigues
- Francisco Silva
- Pedro Abreu
- Joao Pestana
- Ngoc Thi Nguyen
- admin
- Huber Flores
- Petteri Nurmi
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2023-06-12T00:00:00Z"
doi: "https://doi.org/10.1145/3596245"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-12T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"] 
#publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the *ACM Transactions on Internet of Things* Volume 7, Issue 2, 1 - 27
publication_short: In *ACM Transactions on Internet of Things* 7(2), 1 - 27

abstract: "Computing research is increasingly addressing underwater environments and examining how computing can support diving and other activities. Unlike on land, where well-established positioning methods are widely available, underwater environments lack a common positioning mechanism, which is a prerequisite for many applications. Dead reckoning, the use of angle and distance estimates to track position changes from a known point of origin, is a promising candidate for underwater positioning as it does not rely on wireless signals (which decay rapidly in underwater environments) and as there is a wide range of literature and algorithms freely available. Yet, currently it is unclear whether the existing techniques can be adopted in underwater environments or whether the differences in medium and environment affect the performance of the dead reckoning techniques. We contribute by evaluating and systematically analyzing the performance and trade-offs associated with dead reckoning techniques in underwater environments. We present AEOLUS, a prototype unit comprising of a low-cost microcontroller and inertial measurement unit, to perform experiments on the ground and in underwater environments to assess how well the performance of different techniques translates from ground-based use cases to underwater environments. We benchmark 15 different algorithms and compare their performance in such environments to identify common patterns and dissimilarities, and identify root causes for these differences. The results show that displacement and turn errors can be estimated to within 5% error but that the best performing methods vary between land and underwater environments. We also show that the performance depends on the shape of the motion patterns with some algorithms performing better for hard turns whereas others perform better for gradual, more continuous turns."

# Summary. An optional shortened abstract.
#summary: "..."

#tags:
#- Source Themes

# Display this page in the Featured widget?
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: "https://researchportal.helsinki.fi/files/264183888/radeta_2023_lost_in_the_deep.pdf"
#url_code: ''
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
# ---

# {{% callout note %}}
# Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the *Slides* button to check out the example.
# {{% /callout %}}

# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/).
---