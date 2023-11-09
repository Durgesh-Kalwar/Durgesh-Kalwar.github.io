---
layout: post
title:  "Using General Value Functions to Learn Domain-Backed
Inventory Management Policies"
date:   2023-11-01 22:21:59 +00:00
image: /images/supplygvf.png
categories: research
author: "Durgesh Kalwar"
authors: "<strong>Durgesh Kalwar</strong>, Omkar Shelke, Harshad Khadilkar"
venue: "arxiv, 2023"
arxiv: https://arxiv.org/abs/2311.02125
# code: https://github.com/leonidk/modecfg
# website: https://leonidk.github.io/modecfg
# youtube: https://www.youtube.com/watch?v=r2426BR4r8o
---
In this paper, we utilize GVFs to learn domain-backed inventory management policies. GVFs are trained on domain-critical characteristics such as prediction of stock-out probability and wastage quantity. Using this domain expertise for more effective exploration, we train an RL agent to compute the inventory replenishment quantities for a large range of products (up to 6000), which share aggregate constraints such as the total weight/volume per delivery. Additionally, we showed that the GVF predictions can be used to provide additional domain-backed insights into the decisions proposed by the RL agent.