ansible example for study

ansible-galaxy:

ansible-galaxy install angstwad.docker_ubuntu

ansible-galaxy install tersmitten.oracle-java


install cubedrive:

ansible-playbook pb/install_cubedrive_app_example.yml --extra-vars "@pb/cubedrive_app_vars.json"