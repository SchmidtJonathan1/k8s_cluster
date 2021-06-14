# k8s_cluster
Create k8s cluster

To set up a lab enviroment, you need two++ virutal machines (VirtualBox, VMware ...)

To run the ansible playbook use:
**ansible-playbook -i inventory.ini -K -vv site.yml**

-i  = use inventory file
-K  = become root user
-vv = verbose level two (debug mode)


**Notes:
Add your client hostname, username and userpassword to inventory.yml or use ssl certificate for ansible.**
