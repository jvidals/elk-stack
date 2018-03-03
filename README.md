# elk-stack
Installs and configures Elasticsearch, Logstash, Kibana, Curator, and Apache on CentOS 7 
This does not harden for security. In fact, it disables SELinux.
This does not do an indepth config of Apache

Add an inventory file to the root level Ansible directory containing your targets and target vars.
Use 'ansible-playbook -i INVENTORYFILE site.yml' to run it.

Based on https://www.digitalocean.com/community/tutorials/how-to-install-elasticsearch-logstash-and-kibana-elk-stack-on-centos-7
