---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Inseguendo Fagiani Selvatici: Partial Order Reduction for Guarded Command Languages"
authors: 
- Frank S. de Boer
- einarj 
- Rudolf Schlatte
- S. Lizeth Tapia Tarifa
- Lars Tveito

date: 2020-11-15T08:47:43+02:00
doi: "10.4230/OASIcs.Gabbrielli.10"
# draft: true



# Schedule page publish date (NOT publication's date).
publishDate: 2020-09-13T08:47:43+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["6"]

# Publication name and optional abbreviated publication name.
publication: "Festschrift Maurizio Gabbrielli, 2020.."
publication_short: "Festschrift Maurizio Gabbrielli, 2020"

abstract: "  This paper presents a method for testing whether objects in actor
  languages and active object languages exhibit locally deterministic
  behavior.  We investigate such a method for a class of guarded
  command programs, abstracting from object-oriented features like
  method calls but focusing on cooperative scheduling of dynamically
  spawned processes executing in parallel.  The proposed method can
  answer questions such as whether all permutations of an execution
  trace are equivalent, by generating candidate traces for testing which may lead
  to different final states.
  To prune the set of candidate traces, we employ partial order
  reduction.  To further reduce the set, we introduce an analysis
  technique to decide whether a generated trace is schedulable.
  Schedulability cannot be decided for guarded commands using standard
  dependence and interference relations because guard enabledness is
  non-monotonic.  To solve this problem, we use concolic execution to
  produce linearized symbolic traces of the executed program, which
  allows a weakest precondition computation to decide on the
  satisfiability of guards.
"

# Summary. An optional shortened abstract.
summary: "Festschrift Maurizio Gabbrielli, 2020"

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Artefact
  url: "https://github.com/larstvei/GCL"
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
