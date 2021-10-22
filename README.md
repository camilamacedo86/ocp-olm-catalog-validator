OpenShift OLM Catalog Validator
==

## Overview
It is an external validator which can be used with [Operator-SDK](https://github.com/operator-framework/operator-sdk) to check the vendor-like
criteria to publish solutions on OCP catalog

## Usage

You can test this validator by running:

```sh
$ make build
$ ./bin/ocp-olm-catalog-validator <bundle-path> --optional-values="range==v4.8" --output=json-alpha1
```