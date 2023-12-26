## R CMD check results

0 errors | 0 warnings | 5 notes

* checking package dependencies ... NOTE
Package in Depends/Imports which should probably only be in LinkingTo: ‘RcppArmadillo’

I indeed tried to fix this note by removing RcppArmadillo from Depends/Imports, but this will trigger errors. Since my cpp code is based on RcppArmadillo, it is impossible to remove RcppArmadillo. 

* This is a new release.


