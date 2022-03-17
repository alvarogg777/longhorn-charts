helm template -nstorage longhorn . --set privateRegistry.registrySecret=regcred > longhorn.yaml
