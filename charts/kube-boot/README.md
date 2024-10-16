# Helm Charts Repository - kube-boot

This repository contains Helm charts for various Kubernetes deployments, including `kube-boot`. Follow the steps below to add the repository to your Helm setup and use the charts.

## Purpose of this helm chart

This Helm chart was created to address the lack of simple, configurable charts that include built-in secret management options. Its primary goal is to facilitate the development of a new load-testing instrumentation using OpenTelemetry and Gatling within a Kubernetes environment.
## Prerequisites

- Helm (version 3.x or later)
- Access to this GitHub repository or the hosted version (via GitHub Pages or another Helm repository host).

## Adding the Helm Repository

Run the following steps to add the Helm repository:

```bash
helm repo add kube-boot https://borntoprogram.github.io/helm-charts/
helm install my-kube-boot kube-boot/kube-boot --version 1.0.1
