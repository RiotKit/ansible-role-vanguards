TOR Vanguards Ansible role
==========================

```
Vanguards help guard you from getting vanned... 
```

Installs [Vanguards](https://github.com/mikeperry-tor/vanguards) to protect your TOR connection from various attacks. Special thanks to AnarchoTechNYC, this role was based on [ansible-role-tor](https://github.com/AnarchoTechNYC/ansible-role-tor).

- Requires TOR to be installed
- Recommended to use `ControlSocket` instead of `ControlPort` for security
- Uses PyPy3 instead of Python3 for increased performance and reduced load
- Tested on PyPy 3.6, PyPy 3.8 and Ubuntu 20.04

### FAQ

1. Getting `cannot be read: Operation not permitted` in TOR logs, in Vanguards there is a message `stem.InvalidRequest: Unacceptable option value: Failed to configure rendezvous options. See logs for details.`

You may try to set `Sandbox 0`, unfortunately there were issues with seccomp.

## Installing TOR

Check out [ansible-role-onion](https://github.com/systemli/ansible-role-onion) from a Systemli tech collective.

## Installing TOR with Vanguards bundled already

Check [ansible-role-tor](https://github.com/AnarchoTechNYC/ansible-role-tor) for a complex TOR setup from a New York anarchist tech collective.
