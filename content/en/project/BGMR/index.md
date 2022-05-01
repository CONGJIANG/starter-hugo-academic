---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Bayesian Genetic Mark-Recapture Methods For Estimating Seasonal River Run Size Of Stock Populations"
summary: "A novel Bayesian Genetic Mark-Recapture Methods for estimating abundance."
authors:
- admin
tags: 
- Ecology
categories: 
- Statistical Ecology
date: 2021-06-22T15:20:04+08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Photo by Paul Vecsei"
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

The slides can be found {{% staticref "uploads/SSC2021.pdf" "newtab" %}}here{{% /staticref %}}. And the poster can be found {{% staticref "uploads/EURING2021.pdf" "newtab" %}}here{{% /staticref %}}.

## Abstract

Genetic mark-recapture (GMR) is a statistical technique used in estimating population size in ecology. By combining estimated relative abundance for all the species of interest from genetic data with counts for some species, GMR provides information about the total population size and the contributions of each species.

In this study, we propose a novel Bayesian GMR framework which presents several advantages over current frequentist techniques. First, the Bayesian framework can explicitly incorporate the sampling error from the genetic sample within the model specification to accommodate the fact that the observed relative proportions in the genetic sample differ from those in the population. Second, uncertainty in the estimates is easily obtained from the posterior samples, without the need for approximations or bootstrapping. Third, the Bayesian framework lends itself nicely to eventually incorporating additional sources of data into a single model.

The effectiveness of the new method is investigated via simulation studies and is shown to perform better than the frequentist estimator in a first simple simulation. However, in a second simulation, where some of the stocks have very small relative abundances, the method is very sensitive to the choice of prior. We discuss this matter in the Discussion Section.