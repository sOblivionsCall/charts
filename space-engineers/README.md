# space-engineers

The upstream container for this chart is maintainer by another user [here](https://github.com/mmmaxwwwell/space-engineers-dedicated-docker-linux).

## Installation

Add the Repository to Helm:

    helm repo add soblivionscall https://soblivionscall.github.io/charts/

Install the Chart:

    helm install soblivionscall/space-engineers

## Chart Values

To Do

## Things to know

- Persistent storage does work but in my testing i have found NFS to be too slow and receive this error:
    ```
    ERROR: Could not load necessary assembly dependencies. C# redistributable may be missing. Affected file: file:///Z:\appdata\space-engineers\SpaceEngineersDedicated\DedicatedServer64\SpaceEngineers.ObjectBuilders.dll
    ```

## Changelog

`1.x.x`

Initial implementation; it works but i have more features to add in later revisions.