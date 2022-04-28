# Ansible_workstations
Parametrização de Workstations com Ansible

Os scripts foram criados para a distribuição Ubuntu, sendo a versão 20.04 LTS utilizada como base. 
 - A versão ubuntu_devops.yaml possui ferramentas voltadas para Devops e Administradores de Redes
 - A versão ubuntu_standard.yaml é uma versão light com ferramentas essenciais.  

Instalação do Ansible/GIT/Unzip
sudo apt update && sudo apt install ansible unzip git -y

Clone o Repositório
git clone https://github.com/alexcardoso12/ansible_workstations.git

Comando para executar o Playbook Ansible
ansible-playbook tools/ubuntu_devops.yaml --ask-become-pass
Insira sua senha com permissão root para executar as ações descritas no script
