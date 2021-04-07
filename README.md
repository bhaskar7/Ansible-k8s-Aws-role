# Ansible-k8s-Aws-role
Ansible role to configure K8S Master, K8S Worker Nodes on the above created EC2 Instances using kubeadm.


1. Enter your Access key & secret key in aws_ec2.yml file
2. Go to the ansible.cfg file and upadte current path in the ansibel role .
3. Create your own valut using #ansible-vault create vault.yml & enter your secret key and access key.
4. Make sure your aws key should be present in your current folder & update the key name in the ansible.cfg file
5. run ec2-launch.yml file first.
6. Run ansible --ask-vault-pass main.yml cmd. 
