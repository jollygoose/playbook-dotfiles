Ansible playbook to install the dotfiles manager [yadm](https://github.com/TheLocehiliosan/yadm), and clone a dotfiles repo.

## Requirements

* Ansible, which can be installed in a few ways, such as:
  * ```apt install ansible```
  * ```dnf install ansible```
  * ```python -m pip install ansible``` (in or out of a virtual enviroment)
    
### Run

From the playbook directory:

```
# local
ansible-playbook main.yml --connection=local

# none local
ansible-playbook main.yml
```
