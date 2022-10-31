[![R-CMD-check](https://github.com/daeyounglim/adaptIVPT/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/daeyounglim/adaptIVPT/actions/workflows/R-CMD-check.yaml)


## adaptIVPT

+ `adaptIVPT` is an R package that will help you design and analyze in vitro permeation test (IVPT) data (currently supports parallel replicate design and balanced data).
+ This package contains 4 functions:
    * `msabe` for hypothesis testing (mixed-scaled average bioequivalence)
    * `prms` for calculating passing rates (passing rate mixed scaled)
    * `rss` for reestimating sample size (hence adaptive design)
    * `PRsurface` for plotting passing-rate surfaces (passing-rate surface)

### References
+ [Draft Guidance on Generic 5% Acyclovir Cream](https://www.accessdata.fda.gov/drugsatfda_docs/psg/Acyclovir_topical%20cream_RLD%2021478_RV12-16.pdf)
+ [In Vitro Permeation Test Studies for Topical Drug Products Submitted in ANDAs](https://www.fdanews.com/ext/resources/files/2022/10-21-22-InVitroPermeationTestStudiesdraftguidance.pdf?1666376063)
+ Davit, B. M., Chen, M. L., Conner, D. P., Haidar, S. H., Kim, S., Lee, C. H., Lionberger, R. A., Makhlouf, F. T., Nwakama, P. E., Patel, D. T., Schuirmann, D. J., & Yu, L. X. (2012). Implementation of a reference-scaled average bioequivalence approach for highly variable generic drug products by the US Food and Drug Administration. The AAPS journal, 14(4), 915-924. ([link](https://doi.org/10.1208/s12248-012-9406-x))
+ Potvin, D., DiLiberti, C. E., Hauck, W. W., Parr, A. F., Schuirmann, D. J., & Smith, R. A. (2008). Sequential design approaches for bioequivalence studies with crossover designs. Pharmaceutical Statistics: The Journal of Applied Statistics in the Pharmaceutical Industry, 7(4), 245-262. ([link](https://doi.org/10.1002/pst.294))

## Installation
```r
install.packages("adaptIVPT")
```

## Getting help
If you encounter a clear bug, please file an issue with a minimal reproducible example on [GitHub](https://github.com/daeyounglim/adaptIVPT/issues). For questions and other discussion, please email the [maintainer](daeyoung.lim@uconn.edu).


## Authors
+ Daeyoung Lim <daeyoung.lim@uconn.edu>
+ Elena Rantou <Elena.Rantou@fda.hhs.gov>
+ Jessica Kim <Jessica.Kim@fda.hhs.gov>
+ Sungwoo Choi <Sungwoo.Choi@fda.hhs.gov>
+ Nam Hee Choi <NamHee.Choi@fda.hhs.gov>
+ Stella Grosser <Stella.Grosser@fda.hhs.gov>

## ⚠️ Disclaimer
This package reflects the views of the authors and ***should not*** be construed to represent the FDA's views or policies.