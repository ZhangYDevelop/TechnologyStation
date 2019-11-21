**kubectl 常见命令**

1、kubectl  get pods  --all-namespaces  -w  (监控所有pod的运行情况)

2、kubectl get node (查看集群节点)

3、kubectl get nodes -w (监控节点运行情况)

4、kubeadm reset (重置kubeadm,可重新安装)

5、kubectl get pods  podename  -o wide (查看pod详情信息)

6、kubectl get pods -w (监控pods 的运行情况)

7、kubectl scale rc nginx --replicas=5

8、kubectl delete -f my-nginx.yam

