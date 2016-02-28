RobustPmap (Robust calls of pmap checking for the type of returned values)
=======================================

[![RobustPmap](http://pkg.julialang.org/badges/RobustPmap_0.4.svg)](http://pkg.julialang.org/?pkg=Mads&ver=0.4)

[![Build Status](https://travis-ci.org/JuliaLang/RobustPmap.jl.svg?branch=master)](https://travis-ci.org/JuliaLang/Mads.jl)

[![Coverage Status](https://coveralls.io/repos/JuliaLang/RobustPmap.jl/badge.svg?branch=master)](https://coveralls.io/r/JuliaLang/Mads.jl?branch=master)

RobustPmap is a module of MADS. MADS (Model Analysis & Decision Support) is an open-source [Julia](http://julialang.org) code designed as an integrated high-performance computational framework performing a wide range of model-based analyses:

* Sensitivity Analysis
* Parameter Estimation
* Model Inversion and Calibration
* Uncertainty Quantification
* Model Selection and Averaging
* Decision Support

MADS utilizes adaptive rules and techniques which allows the analyses to be performed with minimum user input.
The code provides a series of alternative algorithms to perform each type of model analyses.

Documentation
=============

All the available MADS modules and functions are described at [madsjulia.github.io](http://madsjulia.github.io/Mads.jl)

Installation
============

After starting Julia, execute:

```
Pkg.add("Anasol")
```

Installation behind a firewall
------------------------------

Julia uses git for package management. Add in the `.gitconfig` file in your home directory:

```
[url "https://"]
        insteadOf = git://
```

or execute:

```
git config --global url."https://".insteadOf git://
```

Set proxies:

```
export ftp_proxy=http://proxyout.<your_site>:8080
export rsync_proxy=http://proxyout.<your_site>:8080
export http_proxy=http://proxyout.<your_site>:8080
export https_proxy=http://proxyout.<your_site>:8080
export no_proxy=.<your_site>
```

For example, if you are doing this at LANL, you will need to execute the 
following lines in your bash command-line environment:

```
export ftp_proxy=http://proxyout.lanl.gov:8080
export rsync_proxy=http://proxyout.lanl.gov:8080
export http_proxy=http://proxyout.lanl.gov:8080
export https_proxy=http://proxyout.lanl.gov:8080
export no_proxy=.lanl.gov
```