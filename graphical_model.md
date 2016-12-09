

### Graphs
src: http://people.cs.ubc.ca/~murphyk/Bayes/bnintro.html
we are interested in directed graph for this section. Directed graph is mostly important in AI and statistics. 
<br>
For Discrete variable - CPD - Directed Model:

<img src="https://github.com/iwbtbh/machine_learning_notes/blob/master/img/1.png" width="500"><br>
The thing to remember here is: ** a node is independent of its non-descendent given its parent(s) ** 
For example, W is independent of C (non-descendent) given S, R(W's parents). Similarly, S is independent of R given C. 

### Bayes Rules
posterior = likelihood * prior / marginal likelihood

### Two Styles 
Bottom up and top down. We can infer about the cause given effect; also, we can get a idea of how cause generate effects. 

### Causation and Correlation
src: http://bayes.cs.ucla.edu/BOOK-2K/causality2-epilogue.pdf

Bayes Net is generative model because it shows how we generate effects from causes. DBN are directed model of 
[stochastic process](https://en.wikipedia.org/wiki/Stochastic_process). Most common DBN(s) are Hidden Markov Model and Linear Dynamics Systems(LDS). Every node in LDS has gaussian distributions. 



                  

