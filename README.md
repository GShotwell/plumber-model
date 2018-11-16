# Deploying ML models via Plumber

This repository provides a working example for deploying a Machine Learning model via the [`plumber`](https://www.rplumber.io) package. It is loosely based off of [a talk](https://github.com/blairj09/bmdd-plumber) given at [Big Mountain Data & Dev](https://www.utahgeekevents.com/events/big-mountain-data-dev/), but this example is drastically simplified.

There are two separate pieces to this example. The [model-api](R/model-api) files provide scripts for both training a simple model and building a Plumber API to serve that model. The [model-input-app](R/model-input-app) files build a simple shiny application to interact with the deployed model API.

---

[![](R/model-input-app/images/app-demo.gif)](http://colorado.rstudio.com/rsc/car-model-app/)
