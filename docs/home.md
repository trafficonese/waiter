[![Travis build status](https://travis-ci.org/JohnCoene/waiter.svg?branch=master)](https://travis-ci.org/JohnCoene/waiter)
[![AppVeyor build status](https://ci.appveyor.com/api/projects/status/github/JohnCoene/waiter?branch=master&svg=true)](https://ci.appveyor.com/project/JohnCoene/waiter)

# waiter

Loading screens for Shiny; programmatically show and hide partial or full page loading screens with spinners or loading bars: [demo](https://shiny.john-coene.com/waiter).

## The Staff

The following staff members will help you keep your clients waiting:

* A waiter - splash loading screens.
* A waitress - loading bars on on elements or whole screen.
* A butler - infinite loading bar.
* A hostess - customizable loading bars.
* A steward - animate the waiter's backgrounds. 
* A garcon - animate images for the waiter. 

## Installation

Install the stable version from [CRAN](https://CRAN.R-project.org/package=waiter):

```r
install.packages("waiter")
```

Install the development version from Github with `remotes` or `devtools`: 

<!-- tabs:start -->

#### **remotes**

``` r
install.packages("remotes")
remotes::install_github("JohnCoene/waiter")
```

#### **devtools**

``` r
install.packages("devtools")
devtools::install_github("JohnCoene/waiter")
```

<!-- tabs:end -->

## Support

If you find this useful, please consider supporting waiter on Github, and do not hesitate to report any issue you may come across.

<!-- Place this tag in your head or just before your close body tag. -->
<script async defer src="https://buttons.github.io/buttons.js"></script>

<a class="github-button" href="https://github.com/sponsors/JohnCoene" data-icon="octicon-heart" aria-label="Sponsor @JohnCoene on GitHub">Sponsor</a> <a class="github-button" href="https://github.com/JohnCoene/waiter/issues" data-icon="octicon-issue-opened" aria-label="Issue JohnCoene/waiter on GitHub">Issue</a> <a class="github-button" href="https://github.com/JohnCoene/waiter" data-icon="octicon-star" data-show-count="true" aria-label="Star JohnCoene/waiter on GitHub">Star</a>

## Credit

The underlying CSS and JavaScript libraries that enable waiter:

- [Please Wait](https://github.com/Pathgather/please-wait)
- [Spinkit CSS](https://tobiasahlin.com/spinkit/)
- [Topbar](https://github.com/buunguyen/topbar)
- [Progress.js](https://usablica.github.io/progress.js/)
- [loading.io](https://loading.io/progress/)
- [loadGo](http://franverona.com/loadgo/)