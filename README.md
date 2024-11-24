# awesome-k8s-resources
### Kubernetes常用工具和资源推荐

#### 工具和库
以下工具是帮助管理、监控、集群部署的常用Kubernetes开源工具。

##### 命令行工具
- **[Helm](https://github.com/helm/helm)** - Kubernetes应用包管理工具，用于管理Charts（预配置的Kubernetes资源包）。
- **[K9s](https://github.com/derailed/k9s)** - 提供命令行界面的Kubernetes集群管理工具。
- **[Kubetail](https://github.com/johanhaleby/kubetail)** - 聚合多个Pod的日志到一个流中。
- **[kubectx + kubens](https://github.com/ahmetb/kubectx)** - 快速切换Kubernetes集群和命名空间。
- **[stern](https://github.com/stern/stern)** - 跟踪多个Pod及其内部容器的日志工具。

##### 集群部署
- **[eksctl](https://github.com/weaveworks/eksctl)** - 用于创建Amazon EKS集群的简单命令行工具。
- **[k3s](https://github.com/rancher/k3s)** - 轻量级Kubernetes，易于安装，用于低资源环境。
- **[kind](https://github.com/kubernetes-sigs/kind)** - 使用Docker容器快速创建本地Kubernetes集群。

##### 自动化与CI/CD
- **[Argo CD](https://github.com/argoproj/argo-cd)** - 基于GitOps的Kubernetes持续交付工具。
- **[Flux2](https://github.com/fluxcd/flux2)** - 基于Kubernetes扩展API的GitOps工具。
- **[Skaffold](https://github.com/GoogleContainerTools/skaffold)** - 为Kubernetes应用程序开发提供持续开发支持的命令行工具。

##### 集群资源管理
- **[KEDA](https://github.com/kedacore/keda)** - Kubernetes事件驱动的自动扩展工具，支持从0自动扩展。
- **[Polaris](https://github.com/FairwindsOps/polaris)** - Kubernetes配置校验工具，确保资源配置符合最佳实践。

##### 网络管理
- **[Calico](https://github.com/projectcalico/calico)** - 开源网络和网络安全解决方案，用于容器、虚拟机等工作负载。
- **[ingress-nginx](https://github.com/kubernetes/ingress-nginx)** - 使用NGINX的Kubernetes Ingress控制器，进行反向代理和负载均衡。

##### 存储管理
- **[Longhorn](https://github.com/longhorn/longhorn)** - 分布式块存储系统，适用于Kubernetes。
- **[OpenEBS](https://github.com/openebs/openebs)** - 易于使用的Kubernetes开源存储解决方案。

##### 测试与故障排查
- **[Chaos Mesh](https://github.com/pingcap/chaos-mesh)** - 云原生Chaos工程平台，用于在Kubernetes中模拟故障。
- **[Litmus](https://github.com/litmuschaos/litmus)** - Chaos工程工具，帮助验证服务在故障情况下的恢复能力。

##### 监控与可视化
- **[Grafana](https://github.com/grafana/grafana)** - 开源数据可视化工具，可以展示和理解集群的监控指标。
- **[Prometheus](https://github.com/prometheus/prometheus)** - 用于Kubernetes集群的系统和服务监控系统。

##### 备份与恢复
- **[Velero](https://github.com/vmware-tanzu/velero)** - 为Kubernetes集群和持久化存储提供备份和恢复工具。

##### 安全与合规
- **[Falco](https://github.com/falcosecurity/falco)** - Kubernetes运行时安全监控工具，用于检测异常行为。
- **[kube-hunter](https://github.com/aquasecurity/kube-hunter)** - Kubernetes集群的安全扫描工具，检测安全漏洞。

##### 服务网格
- **[Istio](https://github.com/istio/istio)** - 连接、管理、保护微服务的开源平台。
- **[Linkerd](https://github.com/linkerd/linkerd)** - 提供透明服务网格，简化微服务的管理。

#### 学习资源
- **[Kubernetes基础指南](https://kubernetes.io/docs/tutorials/kubernetes-basics/)** - Kubernetes集群基础知识介绍和教程。
- **[Kubernetes网络模型指南](https://sookocheff.com/post/kubernetes/understanding-kubernetes-networking-model/)** - 深入了解Kubernetes网络架构。
- **[Kubernetes官方命令手册](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)** - 常用kubectl命令和参数列表。

### 推荐学习途径
- **[Kubernetes The Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way)** - 从零搭建高可用Kubernetes集群的详细教程。
- **[深入Kubernetes安全认证指南](https://github.com/walidshaari/Certified-Kubernetes-Security-Specialist)** - 帮助准备Kubernetes安全认证（CKS）的最佳资料。

这些工具和资源涵盖了Kubernetes生态系统中的重要部分，适用于集群管理、自动化部署、监控、故障排查和安全管理等，适合希望提高Kubernetes技能的用户使用。
