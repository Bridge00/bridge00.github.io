---
permalink: /pubs/crim_recid/
title: ""
---

## Ada-NAV: Adaptive Trajectory-Based Sample Efficient Policy Learning for Robotic Navigation

<font size = "3"> Bhrij Patel, Kasun Weerakoon, Wesley A. Suttle, Alec Koppel, Brian M. Sadler, Amrit Singh Bedi, Dinesh Manocha. </font>





## Abstract

<font size = "3"> Reinforcement learning methods, while effective for learning robotic navigation strategies, are known to be highly sample inefficient. This sample inefficiency comes in part from not suitably balancing the explore-exploit dilemma, especially in the presence of non-stationarity, during policy optimization. To incorporate a balance of exploration-exploitation for sample efficiency, we propose Ada-NAV, an adaptive trajectory length scheme where the length grows as a policy's randomness, represented by its Shannon or differential entropy, decreases. Our adaptive trajectory length scheme emphasizes exploration at the beginning of training due to more frequent gradient updates and emphasizes exploitation later on with longer trajectories. In gridworld, simulated robotic environments, and real-world robotic experiments, we demonstrate the merits of the approach over constant and randomly sampled trajectory lengths in terms of performance and sample efficiency. For a fixed sample budget, Ada-NAV results in an 18% increase in navigation success rate, a 20-38% decrease in the navigation path length, and 9.32% decrease in the elevation cost compared to the policies obtained by the other methods. We also demonstrate that Ada-NAV can be transferred and integrated into a Clearpath Husky robot without significant performance degradation. </font>