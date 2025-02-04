---
html_theme.sidebar_secondary.remove: true
---

# Deploying RAPIDS

Deployment documentation to get you up and running with RAPIDS anywhere.

`````{grid} 1 2 2 3
:gutter: 2 2 2 2

````{grid-item-card}
:link: local
:link-type: doc
{fas}`desktop;sd-text-primary` Local Machine
^^^
Use RAPIDS on your local workstation or server.

{bdg-primary}`docker`
{bdg-primary}`conda`
{bdg-primary}`pip`
{bdg-primary}`WSL2`
````

````{grid-item-card}
:link: cloud/index
:link-type: doc
{fas}`cloud;sd-text-primary` Cloud
^^^
Use RAPIDS on the cloud.

{bdg-primary}`Amazon Web Services`
{bdg-primary}`Google Cloud Platform`
{bdg-primary}`Microsoft Azure`
{bdg-primary}`IBM Cloud`
````

````{grid-item-card}
:link: hpc
:link-type: doc
{fas}`server;sd-text-primary` HPC
^^^
Use RAPIDS on high performance computers and supercomputers.

{bdg-primary}`SLURM`
````

````{grid-item-card}
:link: platforms/index
:link-type: doc
{fas}`network-wired;sd-text-primary` Platforms
^^^
Use RAPIDS on compute platforms.

{bdg-primary}`Kubernetes`
{bdg-primary}`Kubeflow`
{bdg-primary}`Databricks`
````

````{grid-item-card}
:link: tools/index
:link-type: doc
{fas}`hammer;sd-text-primary` Tools
^^^
There are many tools to deploy RAPIDS.

{bdg-primary}`containers`
{bdg-primary}`dask-kubernetes`
{bdg-primary}`dask-operator`
{bdg-primary}`dask-helm-chart`
{bdg-primary}`dask-gateway`
````

````{grid-item-card}
:link: https://github.com/rapidsai/cloud-ml-examples
{fas}`book;sd-text-primary` Cloud ML Examples
^^^
See our [example notebooks repo](https://github.com/rapidsai/cloud-ml-examples) with opinionated deployments of RAPIDS to boost machine learning workflows.

{bdg-primary}`xgboost`
{bdg-primary}`optuna`
{bdg-primary}`mlflow`
{bdg-primary}`ray tune`
````
`````

```{toctree}
:maxdepth: 3
:hidden:
:caption: Deploy RAPIDS on

local
cloud/index
hpc
platforms/index
```

```{toctree}
:maxdepth: 3
:hidden:
:caption: Deploy RAPIDS with

tools/index
```
