# Image Builder for Cluster API

The Image Builder can be used to build images intended for use with Kubernetes [CAPI](https://cluster-api.sigs.k8s.io/) providers. Each provider has its own format of images that it can work with. For example, AWS instances use AMIs, and vSphere uses OVAs.

For detailed documentation, see https://image-builder.sigs.k8s.io/capi/capi.html.

## STFC Build
To build with STFC customisations the following command is used:

`PACKER_VAR_FILES=packer/config/stfc.json make build-qemu-ubuntu-2004`
