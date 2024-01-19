### Title

Neural Spiking Ensembles: Dynamics of Representational Geometry

### Short description and the goals for the BrainHack Vanderbilt

## INTRODUCTION

What are the meaningful changes in the brain with experience, that allows for adaptive behavior? When we look at the coordinated activity across spiking networks of neuronal ensembles, we see a delicate balance of stability and flexibility, as needed for a system that can both learn and remember. In this project, we present a population of simultaneously-recorded neurons from the non-human primate during learning of a complex sequence memory task, and in sleep afterwards. 

These data are exceptionally rich for exploration, but also to address three fundamental questions: 
1. can we decode behavioral states from the ensemble dynamics,
2. what is the core representational geometry of the ensembles (what factors are best preserved/differentiated in low-dimensional spaces, and how does the geometry constrain the computations and dynamics of the network, and finally,
3. does the ensemble activity drift with time and experience, and if so, how?

## GOALS FOR THE BRAINHACK VANDERBILT

Our goals include:

- Being able to understand the format of neuronal spiking and the corresponding behavioral data.
- Use manifold learning techniques (e.g. PCA, tSNE, UMAP, CEBRA) to decode relevant behaviors in complex neural spiking data in low dimensional space.
- Modify manifold learning hyperparameters to achieve best behavioral decoding ability.
- Explore changes in single-cell level or behaviors to elucidate mechanisms of representational drift.

### Link to the Project

https://github.com/neurdylab/physio_QA_manual
https://github.com/neurdylab/physio_QA_dl
[Project Intro. Slides](https://docs.google.com/presentation/d/17mtvgRvHOgMBfqDNFqpqpmmtxAMxbJs3FDHAOWCHSDg)

### Image for the BrainHack Vanderbilt website

https://docs.google.com/presentation/d/17mtvgRvHOgMBfqDNFqpqpmmtxAMxbJs3FDHAOWCHSDg

### Project lead

Richard Song: @richardwsong

### Contributors

Ken Rahman: @RahmanKF22
Sam Abbaspoor: @SAbbaspoor
Kari Hoffman: @perpl_lab

### Main Hub

Vanderbilt

### Skills

- Python and Jupyter Notebook: intermediate/advanced
- Git: intermediate
- Machine Learning: intermediate
- Topological Data Analysis: preferred but not required

### Recommended tutorials for new contributors

#### Programming

- [X] [Python: Writing a script](https://school-brainhack.github.io/modules/python_scripts/)
- [X] [Python: Data analysis with Python](https://school-brainhack.github.io/modules/python_data_analysis/)
- [X] [Python: Visualization](https://school-brainhack.github.io/modules/python_visualization/)
- [X] [Machine learning basics](https://school-brainhack.github.io/modules/machine_learning_basics/)

### Good first issues

- Experiment on neural manifold creation with using different hyperparameters (e.g. n_neighbors or min_dist in UMAP). Different parameters can greatly change the shape of the manifold and thus can affect the ability to decode different behaviors. Afterwards, consider creating UI to visualize neural manifolds across different hyperparameters. Here is a great example.
- Parallelize dimensionality reduction across a set of hyperparameters
- Experiment with which behavioral parameters are most separated in low dimensional space (block type, trial number, time, head position, angular velocity, etc.)
- Explore characteristics that may be leading to representational drift. How is firing rate of the cells changing across trials and over time? What about accuracy, time to perform the task, or reward received?
- Structural Index for Neural Manifolds

### Twitter summary


### Short name for the Discord chat channel (~15 chars)

manifold_tuning

### Please read and follow the BrainHack Code of Conduct

- [X] I agree to follow the [BrainHack Global Code of Conduct](https://brainhack.org/code-of-conduct) during the hackathon.
