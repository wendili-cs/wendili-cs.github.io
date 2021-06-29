---
title: "Meta-learning-based Data Feeding in Stock Market Prediction"
collection: talks
type: "Microsoft Research Project"
permalink: /projects/Meta-learning-based-Data-Feeding
venue: "Machine Learning Group, Microsoft Research Asia"
date: 2020-02-01
location: "Beijing, China"
---

**Supervisor: Xiao Yang**

* Focus on data feeding in stock market prediction. Propose a meta-learning-based method to assign weights to training examples.
  1. For the stock market following different patterns in different periods, build a meta-model that selects the data with a similar pattern of the predicted period. We deal with the problem from temporal, spatial, and label aspects.
  2. Splitting the patterns into linear and nonlinear parts, build an ensemble meta-model to do the example re-weighting.
  3. Finished an academic paper ([*page*](https://wendili-cs.github.io/publication/2021UR-DDG-DA)), it is now in submission.
* Writing the data selection part of the [*Qlib*](https://github.com/microsoft/qlib), a quantitative-research library for online trading.
