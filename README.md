# Role Name

_A brief description of the role goes here._

## Requirements

_Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required._

## Role Variables

```yml
docker_users_to_add_group: []
# - name: "{{ ansible_user }}"
docker_user_shell: /bin/bash
```

## Dependencies

_A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles._

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yml
- hosts: docker
  roles:
    - role: docker
      docker_user_shell: /bin/zsh
      docker_users_to_add_group: "{{ clients }}"
```

## License

GNU AFFERO GENERAL PUBLIC LICENSE

## Author Information

MVladislav
