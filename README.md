# rabbitmq-operators-gitops-demo

demo for RabbitMQ summit 2021 talk

## Tools

* k8s cluster
* argo CD
* RabbitMQ cluster operator and messaging topology operator



## to Solve the previlige error
```
oc adm policy add-scc-to-user anyuid -z rabbit-cluster2-server -n rabbitmq-system4
oc adm policy add-scc-to-user hostaccess -z rabbit-cluster2-server -n rabbitmq-system4
oc adm policy add-scc-to-user hostnetwork -z rabbit-cluster2-server -n rabbitmq-system4
```


