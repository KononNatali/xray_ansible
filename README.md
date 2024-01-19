Install Ansible
1. Use install_ansible.sh
(https://winitpro.ru/index.php/2022/12/22/ustanovka-ansible-linux/)

Проверим доступность всех хостов в файле инвентаризации:

    $ ansible all -m ping --ask-pass 

2. $ ansible-galaxy install -r requirements.yml -p ./roles

3. $ ansible-playbook hysteria.yml