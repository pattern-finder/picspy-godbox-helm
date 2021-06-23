# Godbox
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/godbox)](https://artifacthub.io/packages/search?repo=godbox)

[Godbox](https://github.com/quantumsheep/godbox) is a secure sandboxing system for untrusted code execution.

It uses [isolate](https://github.com/ioi/isolate) which uses specific functionnalities of the Linux kernel, thus godbox not able to run properly outside of Linux.

## Usage
```bash
helm repo add godbox-charts https://quantumsheep.github.io/godbox-helm/charts
helm install my-godbox godbox-charts/godbox
```
