# Helm Charts

[![CircleCI](https://circleci.com/gh/sOblivionsCall/charts/tree/main.svg?style=shield)](https://circleci.com/gh/sOblivionsCall/charts/tree/main)

This repository contains [Helm](https://helm.sh) charts for various projects

* [speedtest-tracker](speedtest-tracker/)
* [space-engineers](space-engineers/)

## Installing Charts from this Repository

Add the Repository to Helm:

    helm repo add soblivionscall https://soblivionscall.github.io/charts/

Example of installing a chart from this repository:

    helm install soblivionscall/speedtest-tracker --set eula.OOKLA_EULA_GDPR=true
