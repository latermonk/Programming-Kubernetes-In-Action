#  POD on NODES 

```
kubectl get pods -n <namespace> -o wide --field-selector=spec.nodeName=<node_name> | awk '{print $1" "$5}' | sort -rn -k 2 | head -10
```

```
kubectl describe node <node_name> | grep -A 10 Containers | awk '{print $2"  "$4}'

```



#   go-micro social server. gin mysql redis mongo docker k8s jaeger grafana     
https://github.com/liangjfblue/gmicro   



#   与kubernetes集群的API通信的Golang（gin）API     
https://github.com/ivanilsonaraujojr/k8sclientgo     






#  Gin脚手架实战开发k8s管理系统(第一波)  

https://www.jtthink.com/course/144




#  Cloud Native Archtect 云原生架构师系列课程     
https://cloudnative365.github.io/keynotes_L4_architect.html     






#    GIN

https://github.com/custer-go/learn-gin   


# Programming-Kubernetes-In-Action


![k8s App ](_image/k8s%20App%20.png)



## Rancher. Using Kubernetes API from Go

https://rancher.com/using-kubernetes-api-go-kubecon-2017-session-recap   
https://github.com/alena1108/kubecon2017  
