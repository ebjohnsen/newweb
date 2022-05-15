---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Backwards Type Analysis of Asynchronous Method Calls"
authors: 
- einarj
- Ingrid Chieh Yu
date: 2008-09-21T22:53:29+02:00
doi: "http://dx.doi.org/10.1016/j.jlap.2008.05.004"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-21T23:29:52+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Logic and Algebraic Programming **77** (1-2): 40-59, 2008. © Elsevier."
publication_short: "Journal of Logic and Algebraic Programming **77** (1-2): 40-59, 2008"

abstract:  "Asynchronous method calls have been proposed to better integrate object orientation with distribution. In the language, asynchronous method calls are combined with so-called processor release points in order to allow concurrent objects to adapt local scheduling to network delays in a very flexible way. However, asynchronous method calls complicate the type analysis by decoupling input and output information for method calls, which can be tracked by a type and effect system. Interestingly, backwards type analysis simplifies the effect system considerably and allows analysis in a single pass. This paper presents a kernel language with asynchronous method calls and processor release points, a novel mechanism for local memory deallocation related to asynchronous method calls, an operational semantics in rewriting logic for the language, and a type and effect system for backwards analysis. Source code is translated into runtime code as an effect of the type analysis, automatically inserting inferred type information in method invocations and operations for local memory deallocation in the process. We establish a subject reduction property, showing in particular that method lookup errors do not occur at runtime and that the inserted deallocation operations are safe."

# Summary. An optional shortened abstract.
summary: "Journal of Logic and Algebraic Programming **77** (1-2): 40-59, 2008"

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
