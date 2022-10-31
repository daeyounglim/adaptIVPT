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

## Comments
> You have one example in PRsurface.Rd wrapped in if(interavtive()). Is
this really necessary? If not please unwrap or put it in \donttest if it
takes > 5 sec. If this is needed here, please explain in the example why
that is.

`PRsurface` visualizes a 3D surface, using `persp3d` of {rgl} under the hood. {rgl} provides an interactive viewpoint navigation (e.g., rotating the 3D object, zooming in and out with the mouse wheel, etc). It doesn't take more than 5 seconds but it had to be suppressed without interactivity. I can change it to \donttest if explicitly asked, but as far as I know, CRAN reserves this for when the test takes more than 5 seconds, which the example doesn't satisfy.

## Downstream dependencies
There are no downstream dependencies for this package.

