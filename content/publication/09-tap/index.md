---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Dynamic Symbolic Execution for Testing Distributed Objects"
authors: ["Andreas Griesmayer", "Bernhard Aichernig", "Einar Broch Johnsen", "Rudolf Schlatte"]
date: 2009-07-21T22:55:26+02:00
doi: "http://dx.doi.org/10.1007/978-3-642-02949-3_9"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-21T23:30:00+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *Proc. 3rd Intl. Conf. on Tests And Proofs (TAP'09)*.  LNCS 5668. © Springer 2009."
publication_short: "Proc. TAP 2009"

abstract:  "This paper extends dynamic symbolic execution to distributed and concurrent systems. Dynamic symbolic execution can be used in software testing to systematically identify equivalence classes of input values and has been shown to scale well to large systems. Although mainly applied to sequential programs, this scalability makes it interesting to consider the technique in the distributed and concurrent setting as well. In order to extend the technique to concurrent systems, it is necessary to obtain sufficient control over the scheduling of concurrent activities to avoid race conditions. Creol, a modeling language for distributed concurrent objects, solves this problem by abstracting from a particular scheduling policy but explicitly defining scheduling points. This provides sufficient control to apply the technique of dynamic symbolic execution for model based testing of interleaved processes. The technique has been formalized in rewriting logic, executes in Maude, and applied to non-trivial examples, including an industrial case study."

# Summary. An optional shortened abstract.
summary: "Proc. TAP 2009"

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
