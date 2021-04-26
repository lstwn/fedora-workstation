# fedora workstation ansible setup

```
sudo dnf install ansible
git clone https://github.com/lstwn/fedora-workstation.git
ansible-galaxy install -r requirements.yml
ansible-playbook fedora_workstation.yml --ask-become-pass --ask-vault-pass
```

