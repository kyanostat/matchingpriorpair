# Matching prior pairs

(Written by Michiko Okudo and Keisuke Yano)

This page provides python codes for Matching prior pairs developed in the following paper:

==========================================================================

Paper information: https://arxiv.org/abs/2312.09586

Title: Matching prior pairs connecting Maximum A Posteriori estimation and posterior expectation

Authors: Michiko Okudo (The university of Tokyo), Keisuke Yano (The Institute of Statistical Mathematics)

Abstract: Bayesian statistics has two common measures of central tendency of a posterior distribution: posterior means and Maximum A Posteriori (MAP) estimates. In this paper, we discuss a connection between MAP estimates and posterior means. We derive an asymptotic condition for a pair of prior densities under which the posterior mean based on one prior coin- cides with the MAP estimate based on the other prior. A sufficient condition for the existence of this prior pair relates to α-flatness of the statistical model in information geometry. We also construct a matching prior pair using α-parallel priors. Our result elucidates an interest- ing connection between regularization in generalized linear regression models and posterior expectation.

==========================================================================


## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Usage](#usage)

## Introduction
In Bayesian statistics, two common measures of central tendency of a posterior distribution are posterior mean and Maximum A Posteriori (MAP) estimate.
Our focus is the calibration between the posterior mean and MAP estimate.


## Requirements
- Python 3.x
- Libraries:
  - `numpy`
  - `autograd`
  - `scipy`
  - `pypolyagamma 1.2.3`



## Usage
1. **Run the Jupyter Notebook:**
   
   Open the provided notebook `Matchingpriorpair_v2.ipynb` using Jupyter Notebook:
    ```bash
    jupyter notebook Matchingpriorpair_v2.ipynb
    ```
   Follow the steps in the notebook to reproduce the results.

2. **Use the Functions in Scripts:**
   
   If you want to use the code in standalone Python scripts, refer to the key functions outlined in the notebook. You can import these functions into your own code as needed.

