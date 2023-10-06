# kubernetes-go-client

使用Kubernetes的官方k8s.io库操作Kubernetes资源

## 使用

> 本例使用`Kubernetes`集群的kubeconfig配置文件作为对集群的访问权限
> 你可以根据你的集群的访问权限使用不同的认证方式

1. 将`clientcmd.BuildConfigFromFlags`方法的参数替换为你的集群URL与认证方式, 本示例使用kubeconfig配置文件
2. 运行golang app
```shell
go mod tidy
go run main
```
