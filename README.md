# k3s-install-centos7-rhel7
#Create K3s running cluster on Centos7 or rhel7

## Usage

ansible-playbook site.yaml

Inventory file : hosts.ini
Update your master and node ips there.

## Things playbook will do:
configure all repo and install the k3s

## create kubernetes name space

kubectl create namespace





