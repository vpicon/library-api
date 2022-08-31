# Library API
This repository contains the REST API specification and documentation 
for the Library service. The API is specified using OpenAPI Spec v3.0.

## Checking 
The API specification is style-checked and linted using the YAML 
linting tool [Spectral](https://stoplight.io/open-source/spectral).
The checking is done by providing the `.spectral.yaml` file.

For running the checks so, the Spectral command-line program must be 
installed in the system. And is run with the following command.
```
$ npx @stoplight/spectral-cli lint --ruleset .spectral.yaml spec/openapi.yaml
```
