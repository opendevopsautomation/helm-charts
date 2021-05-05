This repository hosts OpenDevopsAutomation [Helm](https://helm.sh) charts.

## Add Helm repository

```bash
helm repo add opendevopsautomation https://opendevopsautomation.github.io/helm-charts/
helm repo update
```
![image](https://user-images.githubusercontent.com/28804150/117173111-11f2a800-adea-11eb-99d5-4b4e4712de33.png)

## Install chart

```bash
helm upgrade --install app opendevopsautomation/application
```

