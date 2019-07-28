# KubernetesSetupUsingAnsible
An Ansible playbook for setting up Kubernetes using Ansible.


Install SSHFS : https://linuxize.com/post/how-to-use-sshfs-to-mount-remote-directories-over-ssh/


Mounting a directory in Mac:

sudo sshfs -o allow_other,defer_permissions,IdentityFile=~/.ssh/id_rsa root@master:/home/osboxes/Documents/workspace/s
etup/mounted  /Users/ziarehman1/Documents/workspace/KubernetesWorkspace/SetupKubeAnsible/KubernetesSetupUsingAnsible/
