# minimist

##### *Parse Argument Options*

[![Build Status](https://travis-ci.org/jeroenooms/minimist.svg?branch=master)](https://travis-ci.org/jeroenooms/minimist)
[![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/jeroenooms/minimist?branch=master&svg=true)](https://ci.appveyor.com/project/jeroenooms/minimist)
[![Coverage Status](https://codecov.io/github/jeroenooms/minimist/coverage.svg?branch=master)](https://codecov.io/github/jeroenooms/minimist?branch=master)
[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/minimist)](http://cran.r-project.org/package=minimist)
[![CRAN RStudio mirror downloads](http://cranlogs.r-pkg.org/badges/minimist)](http://cran.r-project.org/web/packages/minimist/index.html)
[![Github Stars](https://img.shields.io/github/stars/jeroenooms/minimist.svg?style=social&label=Github)](https://github.com/jeroenooms/minimist)

> A binding to the minimist JavaScript library. This module implements
  the guts of optimist's argument parser without all the fanciful decoration.
  
## Hello World

```r
minimist()
minimist(c("-a", "beep", "-b", "boop"))
args = c("-x", "3", "-y", "4", "-n5", "-abc", "--beep=boop", "foo", "bar", "baz")
minimist(args)
```

## Installation

Binary packages for __OS-X__ or __Windows__ can be installed directly from CRAN:

```r
install.packages("minimist")
```

To install on Linux have a look at [V8 installation instructions](https://github.com/jeroenooms/v8#installation).
