# SpechtLabs Helm Charts

[![Release Charts](https://github.com/SpechtLabs/helm-charts/actions/workflows/release.yaml/badge.svg)](https://github.com/SpechtLabs/helm-charts/actions/workflows/release.yaml)

📦 A collection of **Helm charts** used at SpechtLabs to simplify and standardize Kubernetes deployments.

## 🚀 Available Charts

| Chart Name       | Description                                                                                | Version  |
|------------------|--------------------------------------------------------------------------------------------|----------|
| [hugo-hoster]    | A Helm chart for hosting hugo blogs in Kubernetes with S3 to serve the static content.     | `0.0.9`  |
| [urlshortener]   | A Helm chart for urlshortener, a Kubernetes native URL Shortening and redirection service. | `0.0.16` |
| [static-pages]   | A Helm chart for deploying [Static Pages](https://github.com/SpechtLabs/StaticPages).      | `0.1.3`  |

[hugo-hoster]: ./charts/hugo-hoster/
[urlshortener]: ./charts/urlshortener/
[static-pages]: ./charts/static-pages/

## 📥 Installation

To use a Helm chart from this repository, add the SpechtLabs Helm repository:

```bash
helm repo add spechtlabs https://charts.specht-labs.de
helm repo update
```
