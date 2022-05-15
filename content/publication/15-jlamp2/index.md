---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A proof system for adaptable class hierarchies"
authors: ["Johan Dovland", "Einar Broch Johnsen", "Olaf Owe", "Ingrid Chieh Yu"]
date: 2015-01-21T23:06:40+02:00 
doi: "http://dx.doi.org/10.1016/j.jlamp.2014.09.001"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-21T23:35:16+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Logical and Algebraic Methods in Programming **84** (1): 37-53, 2015. © Elsevier."
publication_short: "Journal of Logical and Algebraic Methods in Programming **84** (1): 37-53, 2015"

abstract: "The code base of a software system undergoes changes during its life time. For object-oriented languages, classes are adapted, e.g., to meet new requirements, customize the software to specific user functionalities, or refactor the code to reduce its complexity. However, the adaptation of class hierarchies makes reasoning about program behavior challenging; even classes in the middle of a class hierarchy can be modified. This paper develops a proof system for analyzing the effect of operations to adapt classes, in the context of method overriding and late bound method calls. The proof system is incremental in the sense that reverification is avoided for methods that are not explicitly changed by adaptations. Furthermore, the possible adaptations are not unduly restricted; i.e., flexibility is retained without compromising on reasoning control. To achieve this balance, we extend the mechanism of lazy behavioral subtyping, originally proposed for reasoning about inheritance when subclasses are added to a class hierarchy, to deal with the more general situation of adaptable class hierarchies and changing specifications. The reasoning system distinguishes guaranteed method behavior from requirements toward methods, and achieves incremental reasoning by tracking guarantees and requirements in adaptable class hierarchies. We show soundness of the proposed proof system."

# Summary. An optional shortened abstract.
summary: "Journal of Logical and Algebraic Methods in Programming **84** (1): 37-53, 2015"

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
