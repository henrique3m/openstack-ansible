Ansible scripts to install Openstack, setup instance with Web Server/Database and deploy application

Edite as configurações no arquivo configure.yml

Arquivos:
	playbooks/
		install.yml
		setup.yml
		deploy.yml
		test.yml
		configure.yml
		templates/
			local.conf.temp

			
Execute os playbooks:
$ansible-playbook install.yml
$ansible-playbook setup.yml
$ansible-playbook deploy.yml
$ansible-playbook test.yml
