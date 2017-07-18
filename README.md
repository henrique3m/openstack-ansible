# Ansible and Openstack

Ansible scripts to install Openstack, setup instance with Web Server/Database and deploy application.

## Playbooks

* dependencies.yml
* install.yml
			
## Execução

```bash
$sudo apt-get install ansible

$git clone https://github.com/henrique3m/openstack-ansible.git

$cd openstack-ansible
```

Edite as configurações de senha nos arquivos openrc.sh e /templates/local.conf.temp

```bash
$ . openrc.sh

$sudo ansible-playbook dependencies.yml 

$ansible-playbook install.yml
```

