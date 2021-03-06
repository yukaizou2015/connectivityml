![](https://raw.githubusercontent.com/yukaizou2015/connectivityml/main/img/banner.jpg)

# Introduction

Welcome to the github repository of connectivityml. This is a team project during the [2021 NeuroHackademy](https://neurohackademy.org/neurohack_year/2021/) Hackathon week, where participants split into teams to work on projects of interest (to view all the projects, see [here](https://github.com/neurohackademy/nh2021-projects)). For connectivityml, the team explored using functional connectivity from the Human Connectome Project (HCP) to predict individual characteristics.

To enhance reproducibility, this repository is in the process of being organized into a clean repository, with one jupyter notebook incorporating all the separate pieces of codes.

The presentation slides may be accessed [here](https://docs.google.com/presentation/d/101WBHWmRxd8VohZk6hZQZg4mVUJ7E0N_X5fWLEVrIaE/edit?usp=sharing).

## Codebook / Key Variables
 - Full details can be found [here](https://wiki.humanconnectome.org/display/PublicData/HCP-YA+Data+Dictionary-+Updated+for+the+1200+Subject+Release)
 - Selected behavioral data:

Column Header | Description
-|-
MMSE_Score | Mini Mental State Examination (MMSE) Completed
PSQI_Score | Pittsburgh Sleep Quality Index (PSQI) Completed
Mars_Final | Mars Final Contrast Sensitivity Score

# References
 - Lundberg, S.M., Lee, S.-I., 2017. [A Unified Approach to Interpreting Model Predictions](https://dl.acm.org/doi/10.5555/3295222.3295230), in: Proceedings of the 31st International Conference on Neural Information Processing Systems, NIPS’17. Curran Associates Inc., Red Hook, NY, USA, pp. 4768–4777.
 - Zhang C, Dougherty CC, Baum SA, White T, Michael AM. [Functional connectivity predicts gender: Evidence for gender differences in resting brain connectivity](https://doi.org/10.1002/hbm.23950). Hum Brain Mapp. 2018;39(4):1765-1776. 

# Resources
 - [HCP1200 Reference Manual](https://www.humanconnectome.org/storage/app/media/documentation/s1200/HCP_S1200_Release_Reference_Manual.pdf)
 - [HCP1200 July 2017 release of high-level rfMRI connectivity analyses](https://www.humanconnectome.org/storage/app/media/documentation/s1200/HCP1200-DenseConnectome+PTN+Appendix-July2017.pdf)
 - [SHAP Values for Explanable AI](https://www.kaggle.com/dansbecker/shap-values)
 - [A model agnostic SHAP calculation](https://towardsdatascience.com/explain-any-models-with-the-shap-values-use-the-kernelexplainer-79de9464897a)
 - [Feature Importance using Random Forest Classifier](https://vitalflux.com/feature-importance-random-forest-classifier-python/)
 - [FSL MELODIC](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/MELODIC)
 - [Gephi: The Open Graph Viz Platform](https://gephi.org/)
