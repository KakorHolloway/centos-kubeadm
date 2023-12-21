# Deploy Kubernetes on centos 9 with kubeadm with docker-ce
Done to be execute with ansible 

# Prerequists

You will need : 

1 lb (will use nginx)
at least 1 master
at least 1 worker

All with centos-9 image.

# Before launch
To launch this playbook, you have to edit hosts file with your ip address, you also have to edit files/hosts to set your VM. 

Don't set master-main adress in masters group 
