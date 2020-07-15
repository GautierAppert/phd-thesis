# PhD thesis - Information k-means, fragmentation and syntax analysis:
# A new approach to unsupervised Machine Learning

PhD undertook at ENSAE and under the supervision of  Olivier Catoni.

## Abstract

* Information $k$-means is a new mathematical framework that 
extends the classical $k$-means criterion, using the 
Kullback divergence as a distortion measure.
The fragmentation criterion is an even broader extension
where each signal is approximated by a combination
of fragments instead of a single center.

* Using the fragmentation criterion as a distortion
measure, we propose a new fragmentation algorithm
for digital signals, conceived as a lossy 
data compression scheme.

* Based on the output of the fragmentation algorithm,
where each signal is described as a random set of 
labels, we describe a new syntax model, conceived as
a lossless data compression scheme.

* Our syntax analysis is based on two principles:
factorization and relabeling of frequent patterns.
It is an iterative scheme, decreasing at each step
as much as possible the length of the representation
of the training set. It produces for each signal 
a syntax tree, providing a multi-level
classification of the signal components.

* We tested the method on grey level digital images,
where it was possible to label successfully 
translated patterns and rotated patterns.
This lets us hope 
that transformation invariant pattern recognition
could be approached in a flexible way using
a general purpose data compression criterion.

* From a mathematical point of view, we derived two 
kinds of generalization bounds. First 
we defined an implicit estimator
based on an implicit statistical model,
related to 
our lossy data 
compression scheme. 
We proved 
a lemma relating the data compression rate
and the distortion level of the compression 
algorithm with the excess risk of 
the statistical estimator. This 
explains why our syntax trees
may be meaningful.

* Second, combining PAC-Bayesian lemmas with the kernel trick,
we proved non asymptotic dimension-free generalization bounds for 
the various information $k$-means and information fragmentation 
criteria we introduced.

* For instance, in the special case of the classical $k$-means 
criterion, 
we get a non asymptotic dimension free generalization bound of order
$O( k \log(k) / n )^{1/4}$
that gives the best sufficient consistency 
condition, namely that the excess risk goes to 
zero when $k \log(k) / n$ goes to zero. Using a new kind of PAC-Bayesian
chaining, we also proved a bound of order 
$O( \log(n/k) \sqrt{k \log(k)/n} )$.









