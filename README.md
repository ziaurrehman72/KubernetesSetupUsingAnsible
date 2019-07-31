# KubernetesSetupUsingAnsible
An Ansible playbook for setting up Kubernetes using Ansible.

Prerequisites:
1. Network connectivity between Master node and Worker nodes
2. Ansible installed on the master node.

Install SSHFS : https://linuxize.com/post/how-to-use-sshfs-to-mount-remote-directories-over-ssh/


Mounting a directory in Mac:

sudo sshfs -o allow_other,defer_permissions,IdentityFile=~/.ssh/id_rsa root@master:/home/osboxes/Documents/workspace/setup/mounted  /Users/ziarehman1/Documents/workspace/KubernetesWorkspace/SetupKubeAnsible/KubernetesSetupUsingAnsible/
