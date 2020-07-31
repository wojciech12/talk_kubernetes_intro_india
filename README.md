# Kubernetes Intro

[slides](slides/) ([pdf](slides/index.pdf))

## Demo

Based on [tutorial](https://github.com/wojciech12/workshop_kubernetes_and_cloudnative):

```
$ kubectl run -i --tty busybox --image=busybox -- sh
# nameservice discovery
$ wget -O - intro-app-svc -q
```

## References

- [Tutorial from Golang Warsaw Meetup](https://github.com/wojciech12/workshop_kubernetes_and_cloudnative)
- [Deployment strategies with k8s](https://github.com/wojciech12/talk_zero_downtime_deployment_with_kubernetes)
- [Monitoring with Prometheus](https://github.com/wojciech12/talk_monitoring_with_prometheus)
