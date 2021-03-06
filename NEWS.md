# HIDDA.forecasting 1.1.0 (2019-03-29)

* Use standard PIT for continuous forecasts (`arima`, `prophet`, `naive`).
  Differences to the previously used non-randomized PIT histograms for
  count data are negligible.

* Add scores for discretized log-normal forecasts, via new function
  `scores_lnorm_discrete()`. These scores are almost identical to the
  continuous scores, essentially due to the large counts.

* Vignettes have been rebuilt using up-to-date versions of all involved
  packages (**forecast** 8.5, **glarma** 1.6.0, **hhh4contacts** 0.13.0,
  **prophet** 0.4, **scoringRules** 0.9.5, **surveillance** 1.17.0)
  in R 3.5.3.


# HIDDA.forecasting 1.0.0 (2018-09-04)

* This is the version used for the book chapter.

* The contained vignettes have been built using R 3.5.1 with all dependent
  packages' versions as of 25 July 2018 from CRAN. The versions of the
  main packages were:

    * [**forecast**](https://CRAN.R-project.org/package=forecast) 8.4
    * [**glarma**](https://CRAN.R-project.org/package=glarma) 1.6.0
    * [**hhh4contacts**](https://CRAN.R-project.org/package=hhh4contacts) 0.13.0
    * [**prophet**](https://CRAN.R-project.org/package=prophet) 0.3.0.1
    * [**scoringRules**](https://CRAN.R-project.org/package=scoringRules) 0.9.4
    * [**surveillance**](https://CRAN.R-project.org/package=surveillance) 1.16.2
