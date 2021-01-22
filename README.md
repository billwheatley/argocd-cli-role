ArgoCD CLI Ansible Role
=========

Role to install the Argo CD CLI client and setup bash completion.

This is based on official Argo CD Documentation: <https://argoproj.github.io/argo-cd/cli_installation/>

This is designed as part of a desktop provisioning playbooks found here <https://github.com/billwheatley/provision-desktop>

Requirements
------------

An internet connection with connectivity to [github](https://github.com)

Role Variables
--------------

none

Dependencies
------------

none

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
    - role: argocd-cli-role
```

License
-------

GPLv2

Author Information
------------------

Contact via [Github](https://github.com/billwheatley/)
