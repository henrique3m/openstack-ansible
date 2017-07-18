# Ansible and Openstack

Ansible scripts to install Openstack.

## Playbooks

* dependencies.yml
* install.yml
* setup.yml
			
## Execução
Edite as configurações de senha nos arquivos openrc.sh e /templates/local.conf.temp

```bash
$ . openrc.sh

$ansible-playbook dependencies.yml 

$ansible-playbook install.yml
```
Download ubuntu image and launch instance

```bash
$ansible-playbook setup.yml
```

