# JMeter Helm Charts

[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/jmeter)](https://artifacthub.io/packages/search?repo=jmeter)

本 [Helm](https://helm.sh) 仓库用于将JMeter的不同Chart安装到 [Kubernetes](https://kubernetes.io)

[English](README_en.md)

### 添加 Helm 仓库

运行下述命令，即可安装仓库

```bash
helm repo add jmeter https://liukunup.github.io/helm-charts
helm repo update
```

### Helm Charts

* [JMeter](https://liukunup.github.io/helm-charts/)

  ```bash
  helm install my-release jmeter/jmeter
  ```

  ```bash
  helm delete my-release
  ```

  Looking for [JMeter Docker Image](https://github.com/liukunup/JMeter)

### Apache JMeter

- [Apache JMeter Distributed Testing Step-by-step](https://jmeter.apache.org/usermanual/jmeter_distributed_testing_step_by_step.html)
