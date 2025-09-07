# Ansible-Playbooks
This repository contains the playbooks for different Configuration Management Files.

Ansible works on PUSH based Mechanism and it's and Agentless, which means there is not agen installed at client side, like CHEF or PUPPET.

3 concepts: Adhoc commands, Modules and playbooks.
1- Adhoc commands are basically linux commands for small use cases.
2- Modules are something which are also yaml files, but will get in form of commands to run set of executions.
3- Playbook is a combination of multiple modules which help us to write configuration management.
4- We have concept of roles in Ansible, which basically helps to segregate and re-use the code, instead of writing multiple playbooks.