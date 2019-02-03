# IPFS Testbed

This chart defines an IPFS testable deployment using [JS-IPFS](https://github.com/ipfs/js-ipfs) and [Toxiproxy](https://github.com/Shopify/toxiproxy).

Before reading forward some notes:
  * This is prepared to be used with JS-IPFS, however it could possible be changed to work with GO-IPFS too with little effort I would say
  * The default image used by this chart is a [personal fork of mine](https://gitlab.com/jgantunes/js-ipfs/container_registry) tailored to be used for testing [Pulsarcast](https://github.com/JGAntunes/js-pulsarcast) and support specific configuration. Feel free to change for whatever you want.

## Install

```
helm repo add jgantunes https://jgantunes.github.io/helm-charts
helm install jgantunes/ipfs-testbed

```

## Configuration

Check the [config](./values.yaml) for all the supported values.
