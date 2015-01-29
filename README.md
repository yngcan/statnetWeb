statnetWeb
==========

This is an R-shiny interface for the statnet suite of R packages. It currently incorporates functionality from the ergm, network and sna packages, allowing users to fit and assess exponential random graph models via GUI.

Run the app in two ways:  
* Through the shinyapps server with this link: https://ebey.shinyapps.io/statnetWeb  
* On your own machine through RStudio:  
    `install.packages(c("statnet", "shiny", "shinyBS", "RColorBrewer", "lattice", "latticeExtra"))`  
    `shiny::runGitHub("statnetWeb", "statnet")`

*Note:* We will keep the master branch on this page consistent with the version deployed on shinyapps. Active development will occur on separate production branches. No branch other than master should be considered stable.

statnet wiki:  
https://statnet.csde.washington.edu/trac 

statnet packages on CRAN:  
http://cran.r-project.org/web/packages/ergm/  
http://cran.r-project.org/web/packages/network/  
http://cran.r-project.org/web/packages/sna/

#### New in v0.3.0

* Access term documentation within Fit Model page
* Customize MCMC control parameters when fitting a model or simulating from a model
* Save up to five different models for a single network
* Compare coefficients and AIC/BIC scores across models
* Switch between models when looking at MCMC Diagnostics, GOF and Simulations
* Compare GOF plots across saved models in a comprehensive chart
* Plot simulation statistics compared to target statistics
* Arrow icons for page navigation
