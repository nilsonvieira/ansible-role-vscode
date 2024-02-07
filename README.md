# How to Install
Configure the `requirements.yml` file.
```
- name: vscode
  src: https://github.com/nilsonvieira/ansible-role-vscode
  version: main
```
In the Roles include:
```
  roles:
    - vscode
```
Execute the command to install role.

```bash
ansible-galaxy role install -r requirements.yml
```