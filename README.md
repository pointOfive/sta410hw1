# UofT STA410/2102 Statistical Computation
## Programming Homework Assignment 1

[Programming Homework Assignment 1](sta410hw1.ipynb)  introduces Python through the following foundational computational and statistical computation problems:

1. Bit string representation of integer value numbers
2. Pseudorandom integer generation with modulus
3. Floating-point error accumulation reduction
4. High precision single pass variance calculations

### Accessing Programming Homework Assignment 1
UofT students may access this the collection of programming problems with the [UofT JupyterHub](https://jupyter.utoronto.ca) via

> https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https://github.com/pointOfive/sta410hw1&branch=master

Some notes to faciltate getting started in this environment are available on the UofT JupyterHub [support page](https://act.utoronto.ca/jupyterhub-support/).
If for some reason JupyterHub is not loading the repository, you can delete and reload repositories (after downloading and saving what you need).  

> From JupyterHub, open a new terminal with `New` > `Terminal` and then use `yes y | rm -r <path to directory to delete>` to a delete the repository directory.

Alternatively, the programming problems may also be accessed without UofT authentication using [Google Colab](https://colab.research.google.com) via

> https://colab.research.google.com/github/pointOfive/sta410hw0/blob/master/sta410hw1.ipynb

If you're working in some other environment, 
the versioning there must support [notebook format 4.5](https://github.com/jupyterlab/jupyterlab/issues/9729), e.g., 
[jupyterlab](https://jupyter.org/install) version 
[3.0.13 or greater](https://github.com/jupyterlab/jupyterlab/releases/tag/v3.0.13); 
otherwise, your notebook cell-ids will not be supported and you will not get any credit for your submitted homework.

> You may check if cell ids are present or changing at each save with `! grep '"id":' <path/to/notebook>.ipynb`
