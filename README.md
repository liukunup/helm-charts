# JMeter Helm Charts

[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/jmeter)](https://artifacthub.io/packages/search?repo=jmeter)

本 [Helm](https://helm.sh) 仓库用于将JMeter的不同Chart安装到 [Kubernetes](https://kubernetes.io)

[English](README_en.md)

### 添加 Helm 仓库

运行下述命令，即可安装仓库

```bash
helm repo add liukunup https://liukunup.github.io/helm-charts
helm repo update
```

### Helm Charts

* [JMeter](https://liukunup.github.io/helm-charts/)

  安装
  ```bash
  helm install my-release liukunup/jmeter
  ```
  卸载
  ```bash
  helm delete my-release
  ```
