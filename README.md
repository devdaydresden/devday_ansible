# Ansible playbooks for the setup of the Dev Day website applications

## Playbooks

* `0.1_setup_users.yml` -- setup admin user accounts, run directly after cloud init
* `0.2_setup_docker.yml` -- setup docker engine
* `0.3_hardening.yml` -- apply hardening for OS and ssh, after running this
  playbook you will not be able to use root for ssh
* `0.4_install_devday_software.yml` -- install and configure the Dev Day software

## Expected ssh settings

```
Host devday-prod
Hostname web.devday.de
User <your_user_name>
IdentitiesOnly yes
IdentityFile ~/.ssh/id_ed25519_devday
```
