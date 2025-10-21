---
title:          "GeoLayer: Towards Low-Latency and Cost-Efficient Geo-Distributed Graph Stores with Layered Graph"
date:           2026-10-21 00:01:00 +0800
selected:       true
pub:            "IEEE International Conference on Data Engineering (ICDE)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2026"

abstract: >-
  In this paper, we propose GeoLayer, a geodistributed graph storage framework that jointly optimizes graph replica placement and pattern request routing. We first construct a latency-aware layered graph architecture that decomposes the graph topology into multiple layers, aiming to reduce the decision space and computational complexity of the optimization problem, while mitigating the impact of network heterogeneity in geo-distributed environments. Building on the layered graph, we introduce an overlap-centric replica placement scheme to accommodate the diversity of graph pattern accesses, along with a directed heat diffusion model that captures heat conduction and superposition effects to guide data allocation. For request routing, we develop a stepwise layered routing strategy that performs progressive expansion over the layered graph to efficiently retrieve the required data.
cover:          /assets/images/covers/icde_geo_store.png
authors:
  - "<b style='font-weight:900;color:#000;'>Feng Yao</b>"
  - Xiaokang Yang
  - Shufeng Gong
  - Song Yu
  - Yanfeng Zhang
  - Ge Yu
links:
  # Code: https://github.com/GorgeouszzZ/GastCoCo
  #Slides: https://idc-neu.github.io/slides/CCaaS_VLDB25.pdf
---




