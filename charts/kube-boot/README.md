# Purpose of this helm chart

This Helm chart was created to address the lack of simple, configurable charts for spring boot applications.
## Prerequisites

- Helm (version 3.x or later)
- Access to this GitHub repository or the hosted version (via GitHub Pages or another Helm repository host).

## Adding the Helm Repository

Run the following steps to add the Helm repository:

```bash
helm repo add kube-boot https://borntoprogram.github.io/helm-charts/
helm install my-kube-boot kube-boot/kube-boot --version 1.2.2
