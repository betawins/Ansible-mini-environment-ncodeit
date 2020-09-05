# kube-ansible is to install and configure kubernetes with ansible
### How to run playbook
### To setup k8s master and slave please select t2.medium instance
ansible-playbook -i hosts main.yml


### Master k8s server should have atleast 2 core of cpu's(t2.medium)
### How to verify nodes
kubectl get nodes
