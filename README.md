# Axon Server

[Axon Server](https://axoniq.io/product-overview/axon-server) is a zero-configuration message router and event store for the open-source [Axon Framework](https://axoniq.io/product-overview/axon-framework) for event-driven microservices and domain-driven design.

This chart installs the Axon Framework in a single-instance or high-availability ([Axon Server Enterprise](https://axoniq.io/product-overview/axon-server-enterprise)).

## Important

We are in the early stages of releasing our Helm chart for Axon and are actively working on this chart. Consider this repository as being in an "alpha" state.
We expect to do a clean-up prior to an eventual `1.0` release. If you use this repository, your feedback is welcomed and you can open GitHub issues
to ask for help or suggest improvements.

## Quickstart

First, add the Helm chart repository (provided through GitHub Pages with the help of [Chart Releaser](https://github.com/helm/chart-releaser))

```
helm repo add axon https://jdlabsco.github.io/axon-server-helm/repo
```

Then install the chart:

```
helm upgrade --install axon-server axon/axon-server -f your-values-file.yaml
```
