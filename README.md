# argo-dbt-example

## Features
- schedule dbt job
- environment
- snaphot
- incremental

## CD
```console
helm template schedule
```

## Reference
- [fishtown-analytics/jaffle_shop: A self-contained dbt project for testing purposes](https://github.com/fishtown-analytics/jaffle_shop)
- [Cron Workflows - Argo Workflows - The workflow engine for Kubernetes](https://argoproj.github.io/argo-workflows/cron-workflows/)

## Initialize

```console
helm create schedule
dbt init dbt --adapter bigquery
```
