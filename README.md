# Helm charts
Helm charts!  

* MRBS - Meeting Room Booking System (coming soon)
* XDMoD - [Open XDMoD](https://open.xdmod.org)

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add zorlin https://zorlin.github.io/helm-charts/
```

You can then run `helm search repo zorlin` to see the charts.

To install the <chart-name> chart:

    helm install my-<chart-name> <alias>/<chart-name>

To uninstall the chart:

    helm delete my-<chart-name>

## Support

These were made for personal use and I'm fairly new to K8S so support is limited. 

You're welcome to open a GitHub issue on this repo if you like, however!

## License

[MIT License](./LICENSE)
