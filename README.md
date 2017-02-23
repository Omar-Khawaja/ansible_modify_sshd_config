This playbook uses the usernames listed in the vars directory of the
modify_sshd_config role to generate the **AllowUsers** portion of the
sshd_config template. This will ensure that only those users (besides root)
will have SSH access to the nodes that this playbook is run against regardless
of their method of authentcation (SSH keys or password).
