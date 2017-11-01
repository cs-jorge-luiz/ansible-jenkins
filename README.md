# ansible-jenkins

Gera um ambiente Jenkins já configurado a partir do playbook. 

Pre-requisitos a instalar:
* Ansible
* Vagrant

Antes de executar o playbook subir a maquina virtual usando vagrant.

```
vagrant up

```
Depois de subida a maquina virtual, na raiz do repositorio execute o comando:

```
ansible-playbook -b ansible-jenkins.yml

```
