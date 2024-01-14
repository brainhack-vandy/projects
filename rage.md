### Title

Deriving Resting State Networks and Observing their Behavior Across Age

### Short description and the goals for the BrainHack Vanderbilt

## INTRODUCTION

Since their discovery, resting state networks have elucidated our understanding of cognitive function such as emotion processing, working memory, and daydreaming. Additionally, a collective of scientists believe resting state networks may be a possible biomarker of mental disorders. However, before we can confirm resting state networks point to a characteristic of mental disorders it is important to model how they change across age. Many studies have identified that age does influence the connectivity of resting state networks however which brain regions within resting state networks change specifically needs to be further understood. The goal of this project is to compare methods of how resting state network information are retrieved and potentially model how they change across age. Anyone is welcome to join and will have the opportunity to learn common practices to derive resting state networks. Individuals are asked to have FSL and Matlab on their computers, but this is not a requirement to join however it may limit their contribution.

## GOALS FOR THE BRAINHACK VANDERBILT

Goal 1: Determine if dual regression on matlab gives similar results of FSL dual regression. Level of difficulty 1-2
Goal 2: Determine how resting state networks change across age. Level of difficulty 3

### Link to the Project

https://github.com/neurdylab/physio_QA_manual
https://github.com/neurdylab/physio_QA_dl
[Project Intro. Slides](https://docs.google.com/presentation/d/17mtvgRvHOgMBfqDNFqpqpmmtxAMxbJs3FDHAOWCHSDg)

### Image for the BrainHack Vanderbilt website

https://docs.google.com/presentation/d/17mtvgRvHOgMBfqDNFqpqpmmtxAMxbJs3FDHAOWCHSDg

### Project lead

Kimberly Rogge-Obando, Github: @krogge-obando

### Contributors

Terra Lee

### Main Hub

Vanderbilt

### Skills

We welcome all contributions from various skill sets and levels. This can include opening discussions around improvements to the documenation and/or code base, answering or commenting on questions or issues raised on github, reviewing pull requests.

### Recommended preparation for new contributors

Download FSL and look into FSL melodic and dual_regression
https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FslInstallation

Download AFNI
https://afni.nimh.nih.gov/pub/dist/doc/htmldoc/background_install/install_instructs/index.html

### Good first issues

- Run ICA Melodic on 1 subjects with 10 components and label the networks , may test component numbers
- Use current ICA Melodic values and run dual regression on FSL, with one subject
- Use current ICA Melodic output to run dual regression on MATLAB, save time series and spatial maps with one subject
- Compare Dual Regression timeseries in FSL and MATLAB, generate figures of comparison and correlation

#### Other issues

- Run dual regression with fslrandomise option and fslrandomise separately with age and gender as a covariate and see how these options replicate. Write up the steps for this project.

### Twitter summary



### Short name for the Discord chat channel (~15 chars)

RAGE (Deriving Resting State Networks and Observing their Behavior Across Age)

### Please read and follow the OHBM Code of Conduct

- [X] I agree to follow the [BrainHack Global Code of Conduct](https://brainhack.org/code-of-conduct) during the hackathon.