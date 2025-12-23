The estimation of causal effects from observational data is a cornerstone of computational
medicine, allowing for the prediction of individual patient responses to interventions. This
project investigates how unobserved confounder variables affect deep causal estimators, specifically
focusing on the Treatment-Agnostic Representation Network (TARNet) and its variants.
Using synthetic and semi-synthetic data with known Conditional Average Treatment Effects
(CATE), we quantify estimation error under varying degrees of confounding. While TARNet
variants such as Dragonnet and CFR TARNet (utilizing Wasserstein distance for balancing)
have shown significant improvements over TARNet in estimating CATE, they operate under
the assumption of "no hidden confounding." We conduct a sensitivity analysis, exploring how
confounding effects impact these these advanced models when that assumption is violated.
