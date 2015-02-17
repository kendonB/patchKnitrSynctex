patchKnitrSynctex
=================

code to patch the Synctex file for use  with knitr (similar to `patchDVI` for sweave)

Usage
------

Install the package:
```
devtools::install_github("kendonB/patchKnitrSynctex")
```
Add the command:
```
Rscript -e "library('patchKnitrSynctex'); patchKnitrSynctex('%.synctex')"
```
to your build command in, for example, TexStudio or Texmaker.
Enjoy forward and reverse search with your favourite pdf viewer/Latex/Knitr Editor!

Acknowledgement from Jan Gleixner
-------------
Code was inspired by [patchDVI](http://cran.r-project.org/web/packages/patchDVI/index.html), [RStudio](https://github.com/rstudio/rstudio) and [Synctex](http://itexmac.sourceforge.net/SyncTeX.html) code.
I am not affiliated with [StatET](https://github.com/walware/statet), [Eclipse](http://git.eclipse.org/c/), [Knitr](https://github.com/yihui/knitr), [RStudio](https://github.com/rstudio/rstudio), [Synctex](http://itexmac.sourceforge.net/SyncTeX.html) or [patchDVI](http://cran.r-project.org/web/packages/patchDVI/index.html). They did all the work !

Acknowledgement from Kendon Bell
-------------
Jan Gleixner did the rest of the work! All I did was put it into a package.