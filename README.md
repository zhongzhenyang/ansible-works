ansible example for study

ansible-galaxy:
```
ansible-galaxy install angstwad.docker_ubuntu
ansible-galaxy install tersmitten.oracle-java
```

本机需要安装:
```
sudo apt-get install libxml2-dev libxslt-dev python-dev
pip install lxml
```
ansible-playbook pb/install_cubedrive_app_example.yml --extra-vars "@pb/cubedrive_app_vars.json"