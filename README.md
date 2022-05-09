<h1 align="center"> ANSIBLE WORKSTATIONS </h1>

<img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=RED&style=for-the-badge"/>

### ÍNDICE

* [PREPARAÇÃO](#preparação)
* [INSTALAÇÃO](#instalação-do-ansible-git-e-unzip-arrowforward)
* [CLONAGEM DE REPOSITOORIO](#clonar-o-repositório-arrowforward)
* [EXECUÇÃO DO PLAYBOOK](#comando-para-executar-o-playbook-ansible-arrowforward)
___
### PREPARAÇÃO
Os scripts foram criados para a distribuição Ubuntu, sendo a versão 20.04 LTS utilizada como base. 
 >- A versão ubuntu_devops.yaml possui ferramentas voltadas para Devops e Administradores de Redes
 >- A versão ubuntu_standard.yaml é uma versão light com ferramentas essenciais.  

### INSTALAÇÃO DO ANSIBLE, GIT e UNZIP :arrow_forward:
```bash
> sudo apt update && sudo apt install ansible unzip git -y
```

### CLONAR O REPOSITÓRIO :arrow_forward:
```bash
> git clone https://github.com/alexcardoso12/ansible_workstations.git
```

### COMANDO PARA EXECUTAR O PLAYBOOK ANSIBLE :arrow_forward:
```bash
> ansible-playbook ansible_workstations/ubuntu_devops.yaml --ask-become-pass
```
___
### License
GPLv3

### Author Information
Created by Alex Cardoso

