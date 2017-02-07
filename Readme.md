# Intro to copulas

Copulas are multivariate probability distributions for which the marginal probability distribution of each variable are uniforms. They are used to describe the join distribution of random variables by only relying on the their marginals, and the copulas. Hence, they describe the dependence between variables. There are different families of copulas that can model different types of dependence.


## Topic modeling and Copulas
This repository contains an R notebook that I used to understand the basics of copulas. For a cool application of copulas and topic models, please check our Coling 2016 paper: [Modeling topic dependencies in semantically coherent text spans with copulas](http://aclweb.org/anthology/C16-1166). More details about citing and/or finding the paper: 
```
@InProceedings{balikas-EtAl:2016:COLING,
  author    = {Balikas, Georgios  and  Amoualian, Hesam  and  Clausel, Marianne  and  Gaussier, Eric  and  Amini, Massih R},
  title     = {Modeling topic dependencies in semantically coherent text spans with copulas},
  booktitle = {Proceedings of COLING 2016, the 26th International Conference on Computational Linguistics: Technical Papers},
  month     = {December},
  year      = {2016},
  address   = {Osaka, Japan},
  publisher = {The COLING 2016 Organizing Committee},
  pages     = {1767--1776},
  url       = {http://aclweb.org/anthology/C16-1166}
}
```
Here is also an implementation of the models: [Topic Modeling Repo](https://github.com/balikasg/topicModelling).
