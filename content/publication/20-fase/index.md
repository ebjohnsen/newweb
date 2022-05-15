---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Global Reproducibility through Local Control for Distributed Active Objects"
authors: 
- Lars Tveito
- einarj
- Rudolf Schlatte
date: 2020-04-14T23:08:36+02:00
doi: "https://doi.org/10.1007/978-3-030-45234-6_7"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-21T22:56:37+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *Proc. 23rd International Conference on Fundamental Approaches to Software Engineering* (FASE 2020). LNCS 12076. © Springer 2020."
publication_short: "Proc FASE 2020"

abstract: "Non-determinism in a concurrent or distributed setting may lead to many different runs or executions of a program. This paper presents a method to reproduce a specific run for non-deterministic actor or active object systems. The method is based on recording traces of events reflecting local transitions at so-called stable states during execution; i.e., states in which local execution depends on interaction with the environment. The paper formalizes trace recording and replay for a basic active object language, to show that such local traces suffice to obtain global reproducibility of runs; during replay different objects may operate fairly independently of each other and in parallel, yet a program under replay has guaranteed deterministic outcome. We then show that the method extends to the other forms of non-determinism as found in richer active object languages. Following the proposed method, we have implemented a tool to record and replay runs, and to visualize the communication and scheduling decisions of a recorded run, for Real-Time ABS, a formally defined, rich active object language for modeling timed, resource-aware behavior in distributed systems."

# Summary. An optional shortened abstract.
summary: "Proc FASE 2020"

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
url_video:

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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
