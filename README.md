# local-dev-airflow


## Install helm chart
Before installing this helm chart please provide the correct values in the values file

```
helm dependency update
helm upgrade --install airflow . -n default
```