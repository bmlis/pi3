# pi3
Ansible playbook for provisioning manjaro i3 distribution.

1. Install ansible.
2. Create a ssh key github.pem and add it to your github account.

For dropbox to work:
``` bash
$ rm -rf ~/.dropbox-dist
$ install -dm0 ~/.dropbox-dist
```
because automatic update breaks it. Also disable autostart and just start it in i3.


TODO:
- write better readme
- ???
