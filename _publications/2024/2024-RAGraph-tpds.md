---
title:          "Towards Efficient Graph Processing in Geo-Distributed Data Centers"
date:           2024-02-1 00:01:00 +0800
selected:       true
pub:            "IEEE Transactions on Parallel and Distributed Systems (TPDS)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2024"

abstract: >-
  This work investigates the problem of data placement for graph processing in geo-distributed data centers. The key idea is to migrate boundary vertices with relatively low contributions to algorithm convergence, thereby enabling the relocated boundary vertices to generate and propagate more influential messages and improving the utilization of scarce network resources. Specifically:(1) We introduce a vertex contribution metric to quantify a vertex’s ability to generate and propagate influential messages, which reflects its contribution to algorithm convergence; (2) We propose a contribution-driven boundary migration algorithm that incorporates both contribution metrics and network heterogeneity, enabling the efficient identification and migration of high-contribution vertices near boundaries; (3) Experimental results demonstrate that our algorithm achieves 1.23× to 2.7× performance improvement and reduces WAN costs by 14.7% to 49.4% in geo-distributed graph processing systems. 
cover:          /assets/images/covers/tpds-ragraph.png
authors:
  - "<b style='font-weight:900;color:#000;'>Feng Yao</b>"
  - Feng Yao
  - Qian Tao
  - Shengyuan Lin
  - Yanfeng Zhang
  - Wenyuan Yu
  - Shufeng Gong
  - Qiange Wang
  - Ge Yu
  - Jingren Zhou
links:
---




