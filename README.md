# cnssolve1pt21_docker

Dockerfile to build images that will compile CNSsolve 1.21 (need old version for ultimately working with software at http://aria.pasteur.fr/supplementary-data/x-links)  
NOTE: THE FILE `cns_solve_1.21_all-mp.tar.gz` MUST BE PROVIDED, SEE BELOW. This Dockerfile will handle everything else to result in a freshly compiled version that will run.

**IMPETUS**: The rationale for not using the available pre-compiled CNSsolve binaries is that investigators have developed approaches based on adding abilities to the CNSsolve software and one such process involves adding that in the code before compiling. Therefore, this Dockerfile can be used as a basis for a Dockerfile for such a case. In fact, I have used this Dockerfile as a basis for [this Dockerfile](https://github.com/fomightez/xlmod_docker/) that dockerizes the process outlined [here](http://aria.pasteur.fr/supplementary-data/x-links/readme/view) in order to set up a modified version of CNS to run the scripts for XL-MS Protein assembly. (That software is referred to as XL-MOD in the publication [here](https://www.ncbi.nlm.nih.gov/pubmed/27111507). 


Contents of built image
-----------------------

A Linux-based Docker container with freshly compiled CNSsolve 1.21

Includes:

* Ubuntu-flavor Linux base
* CNSsolve 1.21

*Specific versions and sources are made clear in [the Dockerfile](https://github.com/fomightez/cnssolve1pt21_docker/blob/master/Dockerfile).*  

Use
----

See the bottom of [the Dockerfile](https://github.com/fomightez/cnssolve1pt21_docker/blob/master/Dockerfile) for steps to use it.
