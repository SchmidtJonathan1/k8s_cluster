# k8s_cluster
Create k8s cluster

Add your client hostname, username and userpassword to inventory.yml or use ssl certificate for ansible.

To run the ansible playbook use this command:
ansible-playbook -K -vv -i inventory.yml site.yml

-K  = become root user
-vv = verbose level 2
-i  = use inventory file
