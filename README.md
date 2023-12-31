# ComposeMviDoc
Documentation of MVI architecture for the UI layer of apps using JetBrains Compose

Motivated by the following article:
[Lighten MVI architecture: Delegate responsibilities to new components](https://proandroiddev.com/lighten-mvi-architecture-delegate-responsibilities-to-new-components-7ea27ea54021)


Keeping a common Scaffold, but outside MVI (using Scaffold local state and setter callbacks):
![MVI architecture for JetBrains Compose](./dataFlow-MVI-new.svg)

Maintaining the common Scaffold via a second MVI loop:
![Full MVI architecture for JetBrains Compose](./dataFlow-MVI-multi.svg)