# kubepatch

## CVE Source

https://github.com/kubernetes/kubernetes/pulls?q=is%3Apr+is%3Amerged+label%3Acherry-pick-approved+CVE

https://www.cvedetails.com/vulnerability-list/vendor_id-15867/product_id-34016/Kubernetes-Kubernetes.html

https://cve.mitre.org/cgi-bin/cvekey.cgi?keyword=Kubernetes

## Checkout to the specified patch release

Defined in the [./releases.yml](https://github.com/klts-io/kubepatch/blob/master/releases.yml)

``` bash
make v1.18.18-lts.0
```

## Build

### Build image

``` bash
make build-image
```

[Images artifacts](https://github.com/orgs/klts-io/packages?repo_name=kubepatch)

### Build client and server

``` bash
make build-client
make build-server
```

[Binaries artifacts](https://github.com/klts-io/kubepatch/releases)

### Official patch release

[patch release](https://kubernetes.io/releases/patch-releases/)
