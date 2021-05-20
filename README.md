README
===

####  1 - Instalar Ansible 2.5 ou superior

 sudo apt-get install software-properties-common
 sudo apt-add-repository ppa:ansible/ansible
 sudo apt-get update
 sudo apt-get install ansible

####  2 - Clonar Repositório

 Clonar o repositório "GIT" dentro da pasta atmz.

####  3 - Executar Ansible

Dentro da pasta  `atmz/ansible-elk/ansible`, executar o comando `ansible-playbook -i host_vars/local --ask-become-pass --tags "elk-commons,elastics,kibana,logstash,filebeat" local.yml -vv`.

Após a execução do comando ansible-playbook, aguardar a instalação completa do ambiente. Caso ocorra algum tipo de erro, `verificar permissões, versões e espaço em disco`.

