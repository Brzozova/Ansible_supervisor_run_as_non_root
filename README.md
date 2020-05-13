# Non-root supervisor

Supervisor is running as root by default. 
This playbook will change root user to different user called `dev_user`.
`dev_user` has less priviliges than root and is assigned to www-pub group.

### Playbook scope

- install supervisor deamon
- configure supervisor to run as non-root user


