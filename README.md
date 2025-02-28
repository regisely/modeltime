
<!-- README.md is generated from README.Rmd. Please edit that file -->

# modeltime

<!-- badges: start -->

[![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/modeltime)](https://cran.r-project.org/package=modeltime)
![](http://cranlogs.r-pkg.org/badges/modeltime?color=brightgreen)
![](http://cranlogs.r-pkg.org/badges/grand-total/modeltime?color=brightgreen)
[![R-CMD-check](https://github.com/business-science/modeltime/workflows/R-CMD-check/badge.svg)](https://github.com/business-science/modeltime/actions)
[![Codecov test
coverage](https://codecov.io/gh/business-science/modeltime/branch/master/graph/badge.svg)](https://app.codecov.io/gh/business-science/modeltime?branch=master)
<!-- badges: end -->

> Tidy time series forecasting with `tidymodels`.

## Quickstart Video

For those that prefer video tutorials, we have an [11-minute YouTube
Video](https://www.youtube.com/watch?v=-bCelif-ENY) that walks you
through the Modeltime Workflow.

<a href="https://www.youtube.com/watch?v=-bCelif-ENY" target="_blank">
<p style="text-align:center;">
<img src= "vignettes/modeltime-video.jpg"
alt="Introduction to Modeltime" width="60%"/>
</p>
<p style="text-align:center">
(Click to Watch on YouTube)
</p>

</a>

## Tutorials

-   [**Getting Started with
    Modeltime**](https://business-science.github.io/modeltime/articles/getting-started-with-modeltime.html):
    A walkthrough of the 6-Step Process for using `modeltime` to
    forecast

-   [**Modeltime
    Documentation**](https://business-science.github.io/modeltime/):
    Learn how to **use** `modeltime`, **find** *Modeltime Models*, and
    **extend** `modeltime` so you can use new algorithms inside the
    *Modeltime Workflow*.

## Installation

CRAN version:

``` r
install.packages("modeltime", dependencies = TRUE)
```

Development version:

``` r
remotes::install_github("business-science/modeltime", dependencies = TRUE)
```

## Why modeltime?

> Modeltime unlocks time series models and machine learning in one
> framework

<img src="vignettes/forecast_plot.jpg" width="100%" style="display: block; margin: auto;" />

No need to switch back and forth between various frameworks. `modeltime`
unlocks machine learning & classical time series analysis.

-   **forecast**: Use ARIMA, ETS, and more models coming (`arima_reg()`,
    `arima_boost()`, & `exp_smoothing()`).
-   **prophet**: Use Facebook’s Prophet algorithm (`prophet_reg()` &
    `prophet_boost()`)
-   **tidymodels**: Use any `parsnip` model: `rand_forest()`,
    `boost_tree()`, `linear_reg()`, `mars()`, `svm_rbf()` to forecast

## Forecast faster

> A streamlined workflow for forecasting

Modeltime incorporates a [streamlined workflow (see Getting Started with
Modeltime)](https://business-science.github.io/modeltime/articles/getting-started-with-modeltime.html)
for using best practices to forecast.

<hr>

<div class="figure" style="text-align: center">

<img src="vignettes/modeltime_workflow.jpg" alt="A streamlined workflow for forecasting" width="100%" />
<p class="caption">
A streamlined workflow for forecasting
</p>

</div>

<hr>

## Meet the modeltime ecosystem

> Learn a growing ecosystem of forecasting packages

<div class="figure" style="text-align: center">

<img src="man/figures/modeltime_ecosystem.jpg" alt="The modeltime ecosystem is growing" width="100%" />
<p class="caption">
The modeltime ecosystem is growing
</p>

</div>

Modeltime is part of a **growing ecosystem** of Modeltime forecasting
packages.

-   [Modeltime (Machine
    Learning)](https://business-science.github.io/modeltime/)

-   [Modeltime H2O
    (AutoML)](https://business-science.github.io/modeltime.h2o/)

-   [Modeltime GluonTS (Deep
    Learning)](https://business-science.github.io/modeltime.gluonts/)

-   [Modeltime Ensemble (Blending
    Forecasts)](https://business-science.github.io/modeltime.ensemble/)

-   [Modeltime Resample
    (Backtesting)](https://business-science.github.io/modeltime.resample/)

-   [Timetk (Feature Engineering, Data Wrangling, Time Series
    Visualization)](https://business-science.github.io/timetk/)

## Summary

Modeltime is an amazing ecosystem for time series forecasting. But it
can take a long time to learn:

-   Many algorithms
-   Ensembling and Resampling
-   Machine Learning
-   Deep Learning
-   Scalable Modeling: 10,000+ time series

Your probably thinking how am I ever going to learn time series
forecasting. Here’s the solution that will save you years of struggling.

## Take the High-Performance Forecasting Course

> Become the forecasting expert for your organization

<a href="https://university.business-science.io/p/ds4b-203-r-high-performance-time-series-forecasting/" target="_blank"><img src="https://www.filepicker.io/api/file/bKyqVAi5Qi64sS05QYLk" alt="High-Performance Time Series Forecasting Course" width="100%" style="box-shadow: 0 0 5px 2px rgba(0, 0, 0, .5);"/></a>

[*High-Performance Time Series
Course*](https://university.business-science.io/p/ds4b-203-r-high-performance-time-series-forecasting/)

### Time Series is Changing

Time series is changing. **Businesses now need 10,000+ time series
forecasts every day.** This is what I call a *High-Performance Time
Series Forecasting System (HPTSF)* - Accurate, Robust, and Scalable
Forecasting.

**High-Performance Forecasting Systems will save companies by improving
accuracy and scalability.** Imagine what will happen to your career if
you can provide your organization a “High-Performance Time Series
Forecasting System” (HPTSF System).

### How to Learn High-Performance Time Series Forecasting

I teach how to build a HPTFS System in my [**High-Performance Time
Series Forecasting
Course**](https://university.business-science.io/p/ds4b-203-r-high-performance-time-series-forecasting).
You will learn:

-   **Time Series Machine Learning** (cutting-edge) with `Modeltime` -
    30+ Models (Prophet, ARIMA, XGBoost, Random Forest, & many more)
-   **Deep Learning** with `GluonTS` (Competition Winners)
-   **Time Series Preprocessing**, Noise Reduction, & Anomaly Detection
-   **Feature engineering** using lagged variables & external regressors
-   **Hyperparameter Tuning**
-   **Time series cross-validation**
-   **Ensembling** Multiple Machine Learning & Univariate Modeling
    Techniques (Competition Winner)
-   **Scalable Forecasting** - Forecast 1000+ time series in parallel
-   and more.

<p class="text-center" style="font-size:24px;">
Become the Time Series Expert for your organization.
</p>
<br>
<p class="text-center" style="font-size:30px;">
<a href="https://university.business-science.io/p/ds4b-203-r-high-performance-time-series-forecasting">Take
the High-Performance Time Series Forecasting Course</a>
</p>
