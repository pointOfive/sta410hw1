# UofT STA410/2102 Statistical Computation

Return to STA410 Programming Portfolio Parent Repository [here](https://github.com/pointOfive/STA410_HW/blob/master/README.md#uoft-sta4102102-statistical-computation).

## Submitting Programming Portfolio Assignment 1
Submit `.ipynb` file to [MarkUs](https://markus-ds.teach.cs.toronto.edu/) before the end of the calendar day (EoD) on the due date.

## Programming Portfolio Assignment 1

[Programming Portfolio Assignment 1](sta410hw1.ipynb) practices linear algebra computations with numpy
through the following foundational computational and statistical computation problems:

1. The Gram-Schmidt to orthogonalize vectors
2. Regression fits from a X=QR decomposition
3. The Cholesky covariance matrix decomposition
4. Conjugate gradient methods

### Accessing Programming Portfolio Assignment 1
UofT students may access this the collection of programming problems with the [UofT Jupyter**Hub**](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https://github.com/pointOfive/sta410hw1&branch=master&urlpath=/lab/tree/sta410hw1) via

> https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https://github.com/pointOfive/sta410hw1&branch=master&urlpath=/lab/tree/sta410hw1

- ***Do not*** access this assignment through https://jupyter.utoronto.ca ***unless*** you ***first log out*** and ***then log back in*** with Jupyter**Lab**, i.e., 

||||
|-|-|-|
|![](zzQ6wYzvBehzQgQ7.png)|![](zzQ6wYzvBehzQgQ7.png)|![](zzQ6wYzvBehzQgQ7.png)|

Some notes to faciltate getting started in this environment are available on the UofT JupyterHub [support page](https://act.utoronto.ca/jupyterhub-support/).
If for some reason Jupyter***Lab*** is not loading the repository, you can delete and reload repositories (after downloading and saving your work).  

> From JupyterHub or JupyterLab, open a new terminal with `New` > `Terminal` and then use `yes y | rm -r <path to directory to delete>` to a delete the repository directory.

Alternatively, the programming problems may also be accessed without UofT authentication using [Google Colab](https://colab.research.google.com) via

> https://colab.research.google.com/github/pointOfive/sta410hw1/blob/master/sta410hw1.ipynb

***If you're working in some other environment, 
the versioning there must support [notebook format 4.5](https://github.com/jupyterlab/jupyterlab/issues/9729), e.g., 
[JupyterLab](https://jupyter.org/install) version 
[3.0.13 or greater](https://github.com/jupyterlab/jupyterlab/releases/tag/v3.0.13); 
otherwise, your notebook cell-ids will not be supported and you will not get any credit for your submitted work.***

> You may check if cell ids are present or changing at each save with `! grep '"id":' <path/to/notebook>.ipynb`
