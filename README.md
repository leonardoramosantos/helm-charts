## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```
helm repo add ls-public-helm-charts https://github.io/leonardoramosantos/helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
ls-public-helm-charts` to see the charts.

To install the tfc-plan-notifier chart:

    helm install tfc-plan-notifier ls-public-helm-charts/tfc-plan-notifier

To uninstall the chart:

    helm delete tfc-plan-notifier
