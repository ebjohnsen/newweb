---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "CREDO: Modelling and analysis of evolutionary structures for distributed services"
summary: "A EU FP6 research project 2006-2009."
authors: []
tags: []
categories: []
date: 2015-07-21T21:55:11+02:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image: 
  caption: ""
  focal_point: "Smart"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

CREDO was a STREP project funded under the EU's FP6 programme
2006-2009 (project no 033826). CORDIS website [here](https://cordis.europa.eu/project/id/033826).

In open distributed systems, the availability and requirements of components providing services vary over time. The networks need to dynamically reconfigure communication links between components at run-time in a context-aware manner. This reconfiguration includes the (dis)connection of components, but also the adaptation and updating of both components and the network. Updates may change the computation abilities of components and the coordination abilities of the network. For safety-critical systems, update should not compromise the reliability of services. Updates should be initiated and effectuated in a decentralized manner. No formal model of computation and communication exists today in which end-to-end system evolution can be expressed and validated. The use of formal models and validation techniques will significantly improve the confidence in dynamically reconfigurable systems, which are otherwise error-prone.

This project aims at a compositional modelling and validation framework for dynamically evolving software systems, separating computation, coordination, and scheduling. Exploiting this separation of concerns, we develop a uniform modelling language in which object-oriented components are combined with flexible communication and timing models. A new notion of service interface is essential, allowing separate design and validation of different components and of the network. Interface composition enables end-to-end reasoning about evolving systems. These interfaces specify services and formalize the context awareness needed for run-time coordination and reconfiguration. The framework will help developers design and maintain systems by validating reconfigurations. We focus on automatable and compositional validation techniques, including abstract simulation, synthesis, model-checking, test-generation, and verification of interface compatibility. The usefulness of the framework is assessed through case studies, and by developing an integrated tool.
