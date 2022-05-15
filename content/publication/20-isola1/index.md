---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Assumption-Commitment Types for Resource Management in Virtually Timed Ambients"
authors: 
- einarj 
- Martin Steffen
- Johanna Beate Stumpf
date: 2020-10-29sT09:07:51+02:00
doi: "https://doi.org/10.1007/978-3-030-61362-4_6"
# draft: true

# Schedule page publish date (NOT publication's date).
publishDate: 2020-09-12T09:07:51+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proc.  9th International Symposium On Leveraging
Applications of Formal Methods, Verification and Validation (ISoLA
2020).  LNCS 12476. © Springer 2020"
publication_short: "Proc. ISoLA 2020. LNCS 12476, Springer 2020"

abstract: "This paper introduces a type system for resource management
in the context of nested virtualization. With nested virtualization,
virtual machines compete with other processes for the resources of
their host environment in order to provision their own processes,
which could again be virtual machines. The calculus of virtually timed
ambients formalizes such resource provisioning, extending the
capabilities of mobile ambients to model the dynamic creation,
migration, and destruction of virtual machines. The proposed type
system is compositional as it uses assumptions about the outside of a
virtually timed ambient to guarantee resource provisioning on the
inside. We prove subject reduction and progress for well-typed
virtually timed ambients, expressing that upper bounds on resource
needs are preserved by reduction and that processes do not run out of
resources."

# Summary. An optional shortened abstract.
summary: "Proc. ISoLA 2020. LNCS 12476, Springer 2020"

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
projects: [cumulus]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
