# Ansible and Openstack

Ansible scripts to install Openstack.

## Playbooks

* dependencies.yml
* install.yml
			
## Execução
Edite as configurações de senha nos arquivos openrc.sh e /templates/local.conf.temp

```bash
$ . openrc.sh

$sudo ansible-playbook dependencies.yml 

$ansible-playbook install.yml
```

