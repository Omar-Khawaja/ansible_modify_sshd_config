This playbook replaces the /etc/ssh/sshd_config file on any node it is run
against and then restarts the ssh service so the changes can take effect.

If you are trying to modify ssh access for users, change the AllowUsers line
in the sshd_config template.
