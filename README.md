# Gloabal Values Demo
```
helm install globalvalues ./globalvalues --set global.environment=staging

```

```
helm dependency update chart-dep/
helm dependency build chart-dep
helm install release-name ./chart-dep/
```

