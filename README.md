# bg-ansible
a solution for having zero downtime in your web-apps while adding new versions of apps.

#An ansible playbook for setting up and configuring the VMs. (Nginx or Haproxy, Docker and firewall should be configured)
Step one Creating a config file for ansible named ansible.cfg in /etc/ansible/ansible.cfg.
Step two Creating an ansible-inventory file. Ansible works against multiple managed nodes or “hosts” in your infrastructure at the sametime, using a list or group of lists known as inventory.
Step three is setting up a playbook .yml file that installing and configuring nginx then we should create the nginx.conf and nginx.site.conf.j2 that using for nginx config files in our hosts.
Step four is complete the ins-and-conf.yml playbook and setting up for installing docker and required system packages and firewall configuration include allow access to tcp port 3000 and OpenSSH.
