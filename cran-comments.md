## Test environments

* local OS X install, R 3.3.3
* ubuntu 12.04 (on travis-ci), R 3.3.3
* win-builder (devel and release)

## R CMD check results

0 errors | 0 warnings | 1 note

License components with restrictions and base license permitting such:
  MIT + file LICENSE
File 'LICENSE':
  YEAR: 2017
  COPYRIGHT HOLDER: Scott Chamberlain

## Reverse dependencies

* I have run R CMD check on the 6 downstream dependencies.
  (Summary at <https://github.com/ropensci/gistr/tree/master/revdep>). 
* None had problems.
* All revdep maintainers were notified of the release.

---

This version fixes a bug and changes function name in a dependency 
package in anticipation of a new version of it on CRAN (dplyr).


Thanks!
Scott Chamberlain
