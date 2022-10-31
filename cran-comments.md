## Test environments
* local macOS Big Sur 11.1 R 4.1.0
* local Windows 10, R 4.2.1.
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

There was 1 NOTE (This is my first submission):
```
checking CRAN incoming feasibility ... NOTE
```

## Downstream dependencies
There are no downstream dependencies for this package.

