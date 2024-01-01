# rabbitmq-operators-gitops-demo

demo for RabbitMQ summit 2021 talk

## Tools

* k8s cluster
* argo CD
* RabbitMQ cluster operator and messaging topology operator




* oc adm policy add-scc-to-user hostaccess -z user-rabbit1
* oc adm policy add-scc-to-user anyuid -z user-rabbit1

* oc adm policy add-scc-to-user hostaccess -z user-rabbit1 -n rabbitmq-system2
* oc adm policy add-scc-to-user anyuid -z user-rabbit1 -n rabbitmq-system2
