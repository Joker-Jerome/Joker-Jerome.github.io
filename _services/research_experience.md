---
title: "Research Experience"
date: 2018-11-18T12:33:46+10:00
featured: true
weight: 1
layout: service
---

For the last five years, I have been developing machine learning algorithms for various biomedical applications.


## Development and maintenance of novel statistical frameworks for large-scale gene association tests.


- Maintaining a SQLite database for 23K imputation models trained from various penalized models.
- Developed a novel prediction approach based on bounded-variables least-squares, a penalized regression method with box-constraints, which outperforms elastic-net-based methods by 72.7% in R-squared. 
- Designed an iterative elimination strategy to select uncorrelated features. 
- Built the testing procedure to detect genetic signal with the cross-tissue joint test.  
- Publication: A statistical framework for cross-tissue transcriptome-wide association analysis. Nature Genetics 2019, 51, 568-576. (Python software: github.com/Joker-Jerome/utmost).
- Working paper: An integrative transcriptome-wide association test based on bounded-variable least-squares. (R software: github.com/Joker-Jerome/twas_bvls).

## Patient outcome prediction with kernel-boosting algorithms. 



- Built a general predictive modeling procedure for patient outcome prediction based on both genetic profiles and clinical features, which can be used for a variety of patient outcomes including binary, continuous, and time-to-event outcomes.
- Developed a novel boosting method in which various loss functions are optimized through a series of kernel functions calculated based on pathway annotations. 
- The proposed method outperforms competing methods including random forest, multiple kernel learning, and nonparametric pathway-based regression in multiple real datasets.
- Publication: A pathway-based kernel boosting method for sample classification using genomic data. Genes 2019, 10, 670. (Python software: github.com/Joker-Jerome/PKB).
- Working paper: A general kernel boosting framework integrating pathways for predictive modeling based on genomic data. (Python software: github.com/zengliX/PKB2).

## A recommendation system for drug repositioning with Kolmogorov–Smirnov-based ranking.


- Proposed a multiomics statistical framework which integrates data from different resources and different experimental designs to prioritize drugs which have repurposing potential for a specific disease.
- Implemented a ranking method based on calculating Kolmogorov–Smirnov statistics for multiple drug feature profiles, which turned out to be an effective strategy for repurposed drug ranking (enrichment test p-value 5.3×10-10 ). 
- 2020 Joint Statistical Meeting Presentation: A multi-omics statistical framework for drug repositioning. (R software: github.com/Joker-Jerome/dr_multiomics). 


## Polypharmacy risk assessment based on drug-drug interaction prediction.

- Built deep learning models with TensorFlow and ensemble models with XGBoost to predict the drug-drug interactions.
- Developed the community-based cross-validation procedure to overcome the overfitting by modularity-based community detection. 
- Designed the polypharmacy risk scores based on predicted exposure burden and Cox-regression models based on VA Hospital comprehensive electronic health records.

## Other Projects

- Deep learning models for elucidating the architectures of transcription regulation networks. 
- Bayesian hierarchical models for identification of trait-associated genes for major depressive disorder patients. 
- A Django web application for predicting genetic mutation deleteriousness by ensemble learning. 

