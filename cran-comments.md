This is a resubmission.

## Test environments
* local macOS Monterey 12.6 R 4.1.0
* local Windows 10, R 4.1.3.
* rhub check_for_cran
* win-builder (devel, release, and oldrelease)

## R CMD check results
There was one NOTE on R-hub check:
```
* checking for detritus in the temp directory ... NOTE
 Found the following files/directories:
  'lastMiKTeXException'
```
As noted in [R-hub issue #503](https://github.com/r-hub/rhub/issues/503), this could be due to a bug/crash in MiKTeX and can likely be ignored.

Also,
```
checking CRAN incoming feasibility ... NOTE
Maintainer: 'Daeyoung Lim <daeyoung.lim@uconn.edu>'
```
as this package is not yet on CRAN.

## Responses to Comments
> Please always explain all acronyms in the description text. e.g.: FDA.

It's now spelled out.

## Downstream dependencies
There are no downstream dependencies for this package.

