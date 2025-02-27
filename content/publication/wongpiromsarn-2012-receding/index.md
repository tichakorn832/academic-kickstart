---
title: "Receding Horizon Temporal Logic Planning"
date: 2012-01-01
publishDate: 2020-06-29T03:28:52.983880Z
authors: ["Tichakorn Wongpiromsarn", "Ufuk Topcu", "Richard M. Murray"]
publication_types: ["2"]
abstract: "We present a methodology for automatic synthesis of embedded control software that incorporates a class of linear temporal logic (LTL) specifications sufficient to describe a wide range of properties including safety, stability, progress, obligation, response and guarantee. To alleviate the associated computational complexity of LTL synthesis, we propose a receding horizon framework that effectively reduces the synthesis problem into a set of smaller problems. The proposed control structure consists of a goal generator, a trajectory planner, and a continuous controller. The goal generator reduces the trajectory generation problem into a sequence of smaller problems of short horizon while preserving the desired system-level temporal properties. Subsequently, in each iteration, the trajectory planner solves the corresponding short-horizon problem with the currently observed state as the initial state and generates a feasible trajectory to be implemented by the continuous controller. Based on the simulation property, we show that the composition of the goal generator, trajectory planner and continuous controller and the corresponding receding horizon framework guarantee the correctness of the system with respect to its specification regardless of the environment in which the system operates. In addition, we present a response mechanism to handle failures that may occur due to a mismatch between the actual system and its model. The effectiveness of the proposed technique is demonstrated through an example of an autonomous vehicle navigating an urban environment. This example also illustrates that the system is not only robust with respect to exogenous disturbances but is also capable of properly handling violation of the environment assumption that is explicitly stated as part of the system specification."
featured: false
publication: "*IEEE Transactions on Automatic Control*"

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
projects: ["formal-methods"]

url_video: https://youtu.be/3HMOa-UsSPc
---
