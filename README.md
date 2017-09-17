# cnssolve1pt21_docker

Dockerfile to build images that will compile CNSsolve 1.21 (need old version for ultimately working with software at http://aria.pasteur.fr/supplementary-data/x-links)  
NOTE: THE FILE `cns_solve_1.21_all-mp.tar.gz` MUST BE PROVIDED, SEE BELOW. This Dockerfile will handle everything else to result in a freshly compiled version that will run.



Contents of built image
-----------------------

A Linux-based Docker container with frshly compiled CNSsolve 1.21

Includes:

* Ubuntu base
* CNSsolve 1.21

*Specific versions and sources are made clear in [the Dockerfile](https://github.com/fomightez/cnssolve1pt21_docker/blob/master/Dockerfile).*  

Use
----

See the bottom of [the Dockerfile](https://github.com/fomightez/cnssolve1pt21_docker/blob/master/Dockerfile) for steps to use it.
