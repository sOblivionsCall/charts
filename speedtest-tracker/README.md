# speedtest-tracker

I take no credit for work on the application, please see the upstream maintainer [here](https://github.com/henrywhitaker3/Speedtest-Tracker)

## Installation

Add the Repository to Helm:

    helm repo add soblivionscall https://soblivionscall.github.io/charts/

Install the Chart:

    helm install soblivionscall/speedtest-tracker --set eula.OOKLA_EULA_GDPR=true

## Chart Values

To Do

## Changelog

`3.x.x`

Added support for probes, still more work to do here for better probes but need to work with the upstream maintainer to improve available endpoints.

`2.x.x`

Added support for persistence

`1.x.x`

Initial implementation; it works but is missing a lot of `normal` expected features.