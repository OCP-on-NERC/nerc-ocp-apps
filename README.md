This repository manages ArgoCD apps deployed on the [nerc-ocp-infra][]
OpenShift cluster.

[nerc-ocp-infra]: https://console-openshift-console.apps.nerc-ocp-infra.rc.fas.harvard.edu/

## Validations make your life easier

### Pre-commit checks

Configure linters to run before each commit by install the
`pre-commit` tool:

```
pip install pre-commit
```

And then enabling it for your working directory. From inside this
repository, run:

```
pre-commit install
```
