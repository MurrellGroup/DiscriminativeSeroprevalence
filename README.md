# Discriminative Bayesian Seroprevalence
Inferring seroprevalence from ELISA data, without choosing a cutoff.

Method explained in [this pdf](https://www.biorxiv.org/content/10.1101/2020.07.14.202150v1), and used for the inference of COVID-19 seroprevalence in Stockholm in [this preprint](https://www.medrxiv.org/content/10.1101/2020.07.17.20155937v1). Code is in [this](https://github.com/MurrellGroup/DiscriminativeSeroprevalence/blob/master/Notebook/Inference.ipynb) notebook. Requires Julia (version > 1).

We take a training set of ELISA measurements (including both negative and positive cases) and population ELISA samples over time, and use both to infer posterior distributions over longitudinal seroprevalence:

<img src="https://github.com/MurrellGroup/DiscriminativeSeroprevalence/blob/master/SimPrev.png" width="400">
