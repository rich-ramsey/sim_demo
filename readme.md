## Background and aims ##

This project simulates multi-level data for a range of factorial designs. It is
designed to give a quick insight into how you might go about determining sample
sizes for experiments using factorial designs using fake-data simulation. 

Most of the content is inspired by two people:

1) Lisa DeBruine and her amazing {faux} R package: https://debruine.github.io/faux/

2) Solomon Kurz and his Bayesian "power" blog post: 
https://solomonkurz.netlify.app/blog/bayesian-power-analysis-part-i/


## Contents ##

1) demo.Rproj

This is the R project file. It is called demo to reflect that this project is a
short demonstration of how you might calculate statistical power via data simulation. 

2) sims.Rmd

This is the main file. It runs through a bunch of simulations for factorial designs
that increase in complexity. It also shows how you can fit regression models using
lme4 or brms and calculate "power" for a range of target sample sizes and 
effect sizes. 

3) /renv/ folder and renv.lock file

This folder and file are used with the package management software renv(). Once
you download the project locally, renv() should automatically kick-in and make
things happen with appropriate package versions.


## Before you start ##

Create three folders in the base directory:

**/data/**

**/figures/**

**/models/**


## To get started ##

Open the sims.Rmd file and start simulating some fake data.
