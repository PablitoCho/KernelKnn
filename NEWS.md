
## KernelKnn 1.0.5

I removed *OpenImageR* and *irlba* as package dependencies. I also added an *init.c* file in the *src* folder due to a change in CRAN submissions for compiled code [  *references* : http://stackoverflow.com/questions/42313373/r-cmd-check-note-found-no-calls-to-r-registerroutines-r-usedynamicsymbols, https://github.com/RcppCore/Rcpp/issues/636  ]


## KernelKnn 1.0.4

I added a try-catch Rcpp function to make possible the calculation of singular covariance matrices as sugggested in https://github.com/mlampros/KernelKnn/issues/1


## KernelKnn 1.0.3

Reimplementation of the Rcpp function due to ASAN-memory-errors


## KernelKnn 1.0.2

I updated the Description file with a URL and a BugReports web-address.


## KernelKnn 1.0.1

Currently, Software platforms like OSX do not support openMP, thus I've made openMP optional for all cpp functions.


## KernelKnn 1.0.0




