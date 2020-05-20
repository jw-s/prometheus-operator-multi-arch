# prometheus-operator-multi-arch
Multi-Arch Images for https://github.com/coreos/prometheus-operator

## Versioning

Images following the same versioning as the upstream repo.

## Images

### Operator

```
docker pull docker.io/joelws/prometheus-operator:$VERSION
```

### Prometheus Config Reloader

```
docker pull docker.io/joelws/prometheus-config-reloader:$VERSION
```

## Supported Architectures 

* arm (arv7/armfh) - Tested on Rasbian Buster
* arm64 - Tested on Ubuntu 20.04 Raspberry Pi 

To request other architectures please make an issue or open a pull requiest. 
