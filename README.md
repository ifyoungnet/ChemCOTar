# ChemCOTar
![GitHub repo size](https://img.shields.io/github/repo-size/ifyoungnet/ChemCOTar)
![GitHub](https://img.shields.io/github/license/ifyoungnet/ChemCOtar)
![GitHub watchers](https://img.shields.io/github/watchers/ifyoungnet/ChemCOTar?style=social)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/numpy)

![scikit-learn](https://img.shields.io/badge/scikit--learn-0.23.0-brightgreen)
![KNIME](https://img.shields.io/badge/KNIME-4.3.3-yellow)

## Rational Design of Organelle-targeted Fluorescent Probes: Insights from Artificial Intelligence
##### ChemCOTar aims to provide a multi-level framework to predict whether a compound is an organelle-targeted probe (B-PvsC model) and which organelles it might target  (M-PvsP model).

##### This repository provides two workflows based on KNIME software:
1) Example workflow for multi-level prediction framework, including: *a, B-PvsC model; b, B-MvsP model; c, M-PvsP model; d, B-McoL model*.
The detailed information about the four models could be found in the paper listed below.
2) Example workflow for application domain.
Compare the <font color="#dd0000">`S indices.TMean`</font> vs `S indices.QMean` and `S indices.TMax` vs `S indices.QMax`. We suggest that a molecule having a `QMean` within 2 fold standard deviation or higher `QMax` is more likely in the application domain. Users should analysis the result according to their own circumstances.

Here is a snapshot:

![snapshot](https://github.com/ifyoungnet/ChemCOTar/blob/main/snapshot%20for%20the%20workflow.svg)

## Publication
> Jie Dong, Jie Qian, Kunqian Yu, Shuai Huang, Xiang Cheng, Fei Chen, Hualiang Jiang, Wen-bin Zeng. Rational Design of Organelle-targeted Fluorescent Probes: Insights from Artificial Intelligence. *Research*, submitted.

## Contact
  
  * Dong Jie: <jiedong@csu.edu.cn> 
