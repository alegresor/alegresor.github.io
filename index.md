---
layout: default
---

* Will be replaced with the ToC, excluding the "Contents" header
{:toc}

# Softwares

## QMCPy

[QMCPy](https://qmcpy.readthedocs.io/en/latest/md_rst/QMCSoftware.html) is a Python package for Quasi-Monte Carlo which includes quasi-random (low discrepancy) sequence generators, automatic variable transforms, adaptive stopping criteria, and a suite of diverse use cases.

```
pip install qmcpy 
```

![image](./assets/ishigami.png)

## FastGaussianProcesses

[FastGaussianProcesses](https://alegresor.github.io/FastGaussianProcesses) is a Python package for fast, exact Gaussian process regression at only $\mathcal{O}(n \log n)$ cost. Support for fast variants of multi-task GPs, GPs with gradient information, and GPs with vector (batch) outputs are also supported. The package builds on the PyTorch stack to enable GPU support and efficient hyperparameter optimization.

![image](./assets/fastgaussianprocesses_logo.svg)

## QMCGenerators.jl

[QMCGenerators.jl](https://alegresor.github.io/QMCGenerators.jl/stable/) is a Julia package for quasi-random (low discrepancy) sequence generators. Lattice and digital sequences, including higher order versions, are supported along with a variety of randomization routines. This is a translation and enhancement of Dirk Nuyens' [Magic Point Shop](https://people.cs.kuleuven.be/~dirk.nuyens/qmc-generators/).

```
] add QMCGenerators
```

![image](./assets/qmcgenerators_logo.svg)


# Posters

## A Neural Surrogate Solver for Radiation Transfer

[2024 NeurIPS Workshop on Data-driven and Differentiable Simulations, Surrogates, and Solvers](https://neurips.cc/virtual/2024/workshop/84720)

<embed src="./posters/2024_RTEDeepONet_NeurIPSD3S3.pdf" type="application/pdf" width="1000" height="1500"/>

## Fast Gaussian Process Regression for Smooth Functions

2024 Illinois Institute of Technology Menger Day 

<embed src="./posters/2024_FastGP_MengerIIT.pdf" type="application/pdf" width="1000" height="750"/>

## Probabilistic Models for PDEs with Random Coefficients

2023 Los Alamos National Laboratory Student Symposium

<embed src="./posters/2023_GP4DarcyPDE_LANL.pdf" type="application/pdf" width="1000" height="750"/>

## Credible Intervals for Probability of Failure with Gaussian Processes

2022 Illinois Institute of Technology Welcome Week Student Research Poster Day

<embed src="./posters/2023_PFGPCredibleIntervals_Own.pdf" type="application/pdf" width="1000" height="750"/>

## Robust Approximation of Sensitivity Indices in QMCPy

[2022 Conference on Sensitivity Analysis of Model Output (SAMO)](https://samo2022.math.fsu.edu/)

<embed src="./posters/2022_SensitivityIndicesQMCPy_SAMO.pdf" type="application/pdf" width="1000" height="750"/>

## QMCPy: Quasi-Monte Carlo Software in Python

2021 Chicago Area Undergraduate Research Symposium

<embed src="./posters/2021_QMCPy_CAURS.pdf" type="application/pdf" width="1000" height="750"/>


## Other Posters

- [QMCPy: A Quasi-Monte Carlo Software in Python 3.](./posters/2021_QMCPy_SIAMCSE.pdf) @ [2021 SIAM Conference on Computational Science and Engineering](https://www.siam.org/conferences/cm/conference/cse21)

- [Multi-threaded/-processed Requests to Cloud Services for Intelligent Address Standardization](./posters/2019_PRLAS_SIAMCSE.pdf) @ [2019 SIAM Conference on Computational Science and Engineering](https://www.siam.org/conferences/cm/conference/cse19)

# Presentations

## Quasi-Monte Carlo and Fast Multi-Task Gaussian Process Regression

2025 Caltech Lunch Group Seminar

<embed src="./presentations/2025_QMCFastMTGPs_Caltech.pdf" type="application/pdf" width="1000" height="600"/>

## Scientific Machine Learning of Radiative Transfer Equations

2024 Illinois Institute of Technology, Department of Applied Mathematics, Computational Mathematics Seminar

<embed src="./presentations/2024_RTEDeepONet_NeurIPSD3S3.pdf" type="application/pdf" width="1000" height="600"/>

## Fast Gaussian Process Regression with Derivative Information using Lattice and Digital Sequences

2024 Illinois Institute of Technology PhD Comprehensive Exam

<embed src="./presentations/2024_PhDComp_IIT.pdf" type="application/pdf" width="1000" height="600"/>

## Probabilistic Models for PDEs with Random Coefficients

2023 Los Alamos National Laboratory Student Lightening Talks

<embed src="./presentations/2023_GP4DarcyPDE_LANL.pdf" type="application/pdf" width="1000" height="600"/>

## Adaptive Probability of Failure Estimation with Gaussian Processes

[2023 SIAM Conference on Computational Science and Engineering](https://www.siam.org/conferences/cm/conference/cse23)

<embed src="./presentations/2023_PFGPErrorBounds_SIAMCSE.pdf" type="application/pdf" width="1000" height="600"/>

## Monte Carlo with QMCPy for Vector Functions of Integrals

[2023 PyData Chicago](https://chicago.pydata.org/)

<embed src="./presentations/2023_QMCPy_PyDataChi.pdf" type="application/pdf" width="1000" height="600"/>

## Unified Framework for Quasi-Monte Carlo Software

[2023 Monte Carlo Methods and Applications](https://mcm2023.sciencesconf.org/)

<embed src="./presentations/2023_UnifiedQMCSoftware_MCM.pdf" type="application/pdf" width="1000" height="600"/>

## Other Presentations

- [Fast Gaussian Process Regression for Smooth Functions using Lattice and Digital Sequences with Matching Kernels](./presentations/2024_HODNKernels_MCQMC.pdf) @ [2024 Monte Carlo and Quasi-Monte Carlo Methods in Scientific Computing Conference](https://uwaterloo.ca/monte-carlo-methods-scientific-computing-conference/)
- [Walsh Functions and Spaces](./presentations/2024_WalshFunctions_IIT.pdf) @ 2024 Illinois Institute of Technology, Department of Applied Mathematics, Computational Mathematics and Multiscale Seminar
- [Fast Physics Informed Kernel Methods for Nonlinear PDEs with Unknown Coefficients](./presentations/2024_kernel_PDE_opterator_learning_SampSci.pdf) @ [2024 SampSci Conference](https://sites.google.com/view/sampsci-2024/home?authuser=0)
- [Fast Gaussian Process Regression with Derivative Information](./presentations/2024_FastGPDerivs_SIAMUQ_MNADay.pdf) @ [2024 SIAM Conference on Uncertainty Quantification](https://www.siam.org/conferences/cm/conference/uq24) and [2024 Midwest Numerical Analysis Day](https://homepage.divms.uiowa.edu/~whan/mwnaday2024.html)
- [QMCPy Client for UM-Bridge](./presentations/2022_QMCPyUMBrige_UMBrigeWorkshop.pdf) @ [2022 UM-Bridge Workshop](https://um-bridge.github.io/workshop/)
- [Quasi-Monte Carlo for Functions of Multi-Dimensional Integrals](./presentations/2022_QMCPyVectorization_MCQMC.pdf) @ [2022 Monte Carlo and Quasi-Monte Carlo Methods in Scientific Computing Conference](https://www.ricam.oeaw.ac.at/events/conferences/mcqmc2022/)
- [QMCPy, A Quasi-Monte Carlo Framework](./presentations/2021_QMCPy_MidwestNumericalAnalysis.pdf) @ [2021 Midwest Numerical Analysis Day](https://web.mst.edu/~hex/MWNAD/MWNAD2021.html)
- [Building QMCPy's Quasi-Monte Carlo Framework.](./presentations/2021_QMCPy_MCM.pdf) @ [2021 International Conference on Monte Carlo Methods and Applications](https://www.uni-mannheim.de/mcm-2021/)
- [QMCPy Quasi-Monte Carlo Software](./presentations/2021_QMCPy_SIAMGL.pdf) @ [2021 SIAM Great Lakes Section Meeting](https://sites.google.com/oakland.edu/glsiam2021/)
- [(Quasi)-Monte Carlo Importance Sampling with QMCPy.](./presentations/2021_QMCPyIS_CompMathIIT.pdf) @ 2021 Illinois Institute of Technology, Department of Applied Mathematics, Computational Mathematics Seminar
- [QMCPy: A Quasi-Monte Carlo Software in Python 3](./presentations/2020_QMCPy_CASSC.pdf) @ [2020 Chicago Area SIAM Student Conference](https://siam-northwestern.github.io/cassc_2020.html)
- [QMCPy: A Quasi-Monte Carlo Software in Python 3.](./presentations/2020_QMCPy_PyDataChicago.pdf) @ [2020 PyData Chicago](https://chicago.pydata.org/)
