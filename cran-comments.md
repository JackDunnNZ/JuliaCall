## Test environments
* local Windows 10, R 3.6.3 with Rtools35
* Windows-latest (on GitHub action), R-release
* macOS-latest (on GitHub action), R-release
* Ubuntu 20.04 (on GitHub action), R-release and R-devel
* win-builder (devel, release, and oldrelease)
* Windows Server 2008 R2 SP1 (on R-hub), R-devel, 32/64 bit
* Ubuntu 16.04 (on R-hub), R-release, GCC
* Debian Linux (on R-hub), R-devel, GCC ASAN/UBSAN
* Fedora Linux (on R-hub), R-devel, clang, gfortran

## R CMD check results

0 errors | 0 warnings | 0 note

## Reverse dependencies
I have also run R CMD check on downstream dependencies of JuliaCall
(https://github.com/Non-Contradiction/JuliaCall/tree/master/revdep).
The summary generated by revdepcheck is at (https://github.com/Non-Contradiction/JuliaCall/tree/master/revdep/README.md)
and (https://github.com/Non-Contradiction/JuliaCall/tree/master/revdep/problems.md).
There are 6 downstream dependencies currently -- convexjlr, diffeqr, iai, knitr, phenofit, and tktdj12r.
-- CHECK ----------------------------------------------------- 6 packages --
√ convexjlr 0.8.1                        -- E: 0     | W: 0     | N: 0      
√ diffeqr 1.0.0                          -- E: 0     | W: 0     | N: 2      
√ iai 1.4.0                              -- E: 0     | W: 0     | N: 0      
√ knitr 1.30                             -- E: 0     | W: 0     | N: 2      
√ phenofit 0.2.7                         -- E: 0-1   | W: 0     | N: 0      
√ tktdjl2r 0.2.0                         -- E: 0     | W: 0     | N: 0    
OK: 6                                                                     
BROKEN: 0
