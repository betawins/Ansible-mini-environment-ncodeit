# kube-ansible is to install and configure kubernetes with ansible
### How to run playbook

ansible-playbook -i hosts main.yml


### Master k8s server should have atleast 2 core of cpu's(t2.medium)
### to verify nodes
kubectl get nodes
