TOR Vanguards Ansible role
==========================

```
Vanguards help guard you from getting vanned... 
```

Installs [https://github.com/mikeperry-tor/vanguards](Vanguards) to protect your TOR connection from various attacks. Special thanks to AnarchoTechNYC, this role was based on [https://github.com/AnarchoTechNYC/ansible-role-tor](ansible-role-tor).

- Requires TOR to be installed
- Recommended to use `ControlSocket` instead of `ControlPort` for security
- Uses PyPy3 instead of Python3 for increased performance and reduced load

## Installing TOR

Check out [ansible-role-onion](https://github.com/systemli/ansible-role-onion) from a Systemli tech collective.

## Installing TOR with Vanguards bundled already

Check [https://github.com/AnarchoTechNYC/ansible-role-tor](ansible-role-tor) for a complex TOR setup from a New York anarchist tech collective.
