---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Lazy Product Discovery in Huge Configuration Spaces"
authors:
- Michael Lienhardt
- Ferruccio Damiani
- einarj 
- Jacopo Mauro
date: 2020-06-21T22:35:11+02:00
doi: "https://doi.org/10.1145/3377811.3380372"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-21T22:35:11+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *Proc. 42nd International Conference on Software Engineering* (ICSE 2020). © ACM Press 2020."
publication_short: "Proc. ICSE 2020"

abstract: "Highly-configurable software systems can have thousands of interdependent configuration options across different subsystems. In the resulting configuration space, discovering a valid product configuration for some selected options can be complex and error prone.  The configuration space can be organized using a feature model, fragmented into smaller interdependent feature models reflecting the configuration options of each subsystem.  We propose a method for lazy product discovery in large fragmented feature models with interdependent features. We formalize the method and prove its soundness and completeness. The evaluation explores an industrial-size configuration space. The results show that lazy product discovery has significant performance benefits compared to standard product discovery, which in contrast to our method requires all fragments to be composed to analyze the feature model. Furthermore, the method succeeds when more efficient, heuristics-based engines fail to find a valid configuration."

# Summary. An optional shortened abstract.
summary: "Proc ICSE 2020"

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: 
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://www.youtube.com/watch?v=t7BmeOKFE_U

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [hyvar]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
