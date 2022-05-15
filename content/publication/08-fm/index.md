---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Lazy Behavioral Subtyping"
authors: ["Johan Dovland", "Einar Broch Johnsen", "Olaf Owe", "Martin Steffen"]
date: 2008-05-21T22:53:39+02:00
doi: "http://dx.doi.org/10.1007/978-3-540-68237-0_6"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-21T23:29:02+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *Proc. 15th Intl. Symposium on Formal Methods (FM'08)*. LNCS 5014, © Springer 2008."
publication_short: "Proc. FM 2008"

abstract:  "Late binding allows flexible code reuse but complicates formal reasoning significantly, as a method call’s receiver class is not statically known.  This is especially true when programs are incrementally developed by extending class hierarchies. This paper develops a novel method to reason about late bound method calls. In contrast to traditional behavioral subtyping, reverification is avoided without restricting method overriding to fully behavior-preserving redefinition. The approach ensures that when analyzing the methods of a class, it suffices to consider that class and its superclasses. Thus, the full class hierarchy is not needed, and incremental reasoning is supported. We formalize this approach as a calculus which lazily imposes context-dependent subtyping constraints on method definitions. The calculus ensures that all method specifications required by late bound calls remain satisfied when new classes extend a class hierarchy.  The calculus does not depend on a specific program logic, but the examples in the paper use a Hoare-style proof system. We show soundness of the analysis method."

# Summary. An optional shortened abstract.
summary: "Proc FM 2008"

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
