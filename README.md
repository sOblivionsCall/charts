# Helm Charts

[![Helm Charts](https://app.circleci.com/gh/soblivionscall/charts.svg?style=svg&circle-token=225fdf161e0cd71a084590cf5a3c2f015705a0a3)](https://github.com/sOblivionsCall/charts/blob/main/README.md)

This repository contains [Helm](https://helm.sh) charts for various projects

* [speedtest-tracker](charts/speedtest-tracker/)

## Installing Charts from this Repository

Add the Repository to Helm:

    helm repo add soblivionscall https://soblivionscall.github.io/charts/

Example of installing a chart from this repository:

    helm install soblivionscall/speedtest-tracker --set eula.OOKLA_EULA_GDPR=true
