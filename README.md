# Forecast [![Dev](https://img.shields.io/badge/docs-dev-blue.svg)](https://viraltux.github.io/Forecast.jl/dev)

Julia package containing utilities intended for Time Series analysis.

> :warning: This package is in an early development stage and its functionality has not been thoroughly tested. Please, consider to report issues if you find any.

## Methods

* Auto-correlation/covariance function and custom plots
* Cros-correlation/covariance function and custom plots
* Henderson Moving Average Filter
* Lagged differences and Reverse lagged differences of a given order
* Locally Estimated Scatterplot Smoothing (LOESS)
* Seasonal and Trend decomposition based on Loess (STL) and custom plot
* Seasonal Plot for series and Time Series
* Simple Moving Average

<img src="./docs/src/images/stl_readme.png">

## Datasets

* Atmospheric Carbon Dioxide Dry Air Mole Fractions from quasi-continuous measurements at Mauna Loa, Hawaii.

K.W. Thoning, A.M. Crotwell, and J.W. Mund (2020), Atmospheric Carbon Dioxide Dry Air Mole Fractions from continuous measurements at Mauna Loa, Hawaii, Barrow, Alaska, American Samoa and South Pole. 1973-2019, Version 2020-08 National Oceanic and Atmospheric Administration (NOAA), Global Monitoring Laboratory (GML), Boulder, Colorado, USA https://doi.org/10.15138/yaf1-bk21 FTP path: ftp://aftp.cmdl.noaa.gov/data/greenhouse_gases/co2/in-situ/surface/

## References

[Cleveland et al. 1990]  Cleveland,  R.  B.;  Cleveland,  W.  S.;McRae, J. E.; and Terpenning, I.  1990.  STL: A seasonal-trend decomposition procedure based on loess. Journal of Official Statistics 6(1):3–73.

[![Coverage](https://codecov.io/gh/viraltux/Forecast.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/viraltux/Forecast.jl)
