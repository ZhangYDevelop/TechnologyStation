**kubectl 常见命令**

1、kubectl  get pods  --all-namespaces  -w  (监控所有pod的运行情况)

2、kubectl get node (查看集群节点)

3、kubectl get nodes -w (监控节点运行情况)

4、kubeadm reset (重置kubeadm,可重新安装)

5、kubectl get pods  podename  -o wide (查看pod详情信息)

6、kubectl get pods -w (监控pods 的运行情况)

7、kubectl scale rc nginx --replicas=5

8、kubectl delete -f my-nginx.yam

9、kubectl delete pods pode-name（删除后会重新创建）

10、kubectl get deployment/replicationcontroller/replicaset (查看不同类型的资源)

11、kubectl set image deployment nginx-deployment nginx=1.9.1 (手动设置镜像版本，deployment 类型的资源镜像会自动跟新版本)

12、 kubectl get namespace (获取命名空间)

13、kubenctl get pods -n  namespace (获取具体命名空间下的pods)

14、创建命名空间  Create a new YAML file called `my-namespace.yaml` with the contents:

15、kubectl delete namespaces <insert-some-namespace-name> （删除命名空))

