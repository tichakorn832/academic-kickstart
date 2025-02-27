---
title: "Incremental minimum-violation control synthesis for robots interacting with external agents"
date: 2014-01-01
publishDate: 2020-06-29T03:28:52.981744Z
authors: ["Pratik Chaudhari", "Tichakorn Wongpiromsarn", "Emilio Frazzoli"]
publication_types: ["1"]
abstract: "We consider the problem of control strategy synthesis for robots that interact with external agents, together known as the environment. Both the robot and the environment are modeled as dynamical systems with differential constraints and take part in a nonzero-sum two-player differential game to fulfill their respective task specifications while satisfying a set of safety rules. They minimize a cost function that is representative of the level of unsafety with respect to these safety rules. Throughout, the problem is motivated by an autonomous car in an urban environment that interacts with other cars in situations such as navigating stop signs at road junctions and single-lane roads. Ideas behind sampling-based motion-planning algorithms are used to incrementally construct a finite Kripke structure abstraction of a continuous dynamical system. Model-checking techniques for safety rules expressed using Linear Temporal Logic (LTL) are then leveraged to propose an algorithm which synthesizes a control strategy for the two-player game. We analyze the algorithm to show that, with probability one, it converges to the Stackelberg equilibrium asymptotically. This algorithm is also demonstrated in a number of simulation experiments."
featured: false
publication: "*2014 American Control Conference*"

# Summary. An optional shortened abstract.
summary: ""

# Digital Object Identifier (DOI)
doi: ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags: []

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["planning-conflicting-specifications"]
---
