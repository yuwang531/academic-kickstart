---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "New manuscript on reinforcement learning for temporal logic specifications"
subtitle: ""
summary: ""
authors: []
tags: ['research']
categories: []
date: 2019-07-19T13:59:03-04:00
lastmod: 2019-07-19T13:59:03-04:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

There is a growing interest on formal methods-based robotic motion planning for temporal logic objectives. In
this work, we extend the scope of existing synthesis methods to
hyper-temporal logics. We are motivated by the fact that important planning objectives, such as optimality, robustness, and
privacy, (maybe implicitly) involve the interrelation between
multiple paths; such objectives are thus hyperproperties, and
cannot be expressed with usual temporal logics like the linear
temporal logic (LTL). We show that such hyperproperties can
be expressed by HyperLTL, an extension of LTL to multiple
paths. To handle the complexity of motion planning with
HyperLTL specifications, we introduce a symbolic approach for
synthesizing planning strategies on discrete transition systems.
Our planning method is evaluated on several case studies.


Check [this](../icra_hyper.pdf) for details.