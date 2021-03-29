# Helm Charts

[![Helm Charts](https://circleci.com/gh/soblivionscall/charts.svg?style=svg&circle-token=a922a23c5bf3e5b5bab9200899de3dd5df3b24cf)](https://app.circleci.com/pipelines/github/sOblivionsCall)

This repository contains [Helm](https://helm.sh) charts for various projects

* [speedtest-tracker](charts/speedtest-tracker/)

## Installing Charts from this Repository

Add the Repository to Helm:

    helm repo add soblivionscall https://soblivionscall.github.io/charts/

Example of installing a chart from this repository:

    helm install soblivionscall/speedtest-tracker --set eula.OOKLA_EULA_GDPR=true
