# targetcli-modules

Modules for interacting with targetcli command line utility.

## Requirements
`targetcli` has to be installed.

## Role Variables

None. This role is intended to be included as dependency.

## Provided Modules

*targetcli_backstore* - create/delete backstore objects ('/backstore')

*targetcli_iscsi* - create/delete iscsi object ('/iscsi')

*targetcli_iscsi_lun* - add/remove luns to/from iscsi object ('/iscsi/.../tpg1/luns')

*targetcli_iscsi_acl* - add/remove acls to/from iscsi object ('/iscsi/.../tpg1/acls')

## Example Playbook

Example playbook for including modules in your playbook

```yml
- hosts: servers
  roles:
   - { role: targetcli-modules }
```

## License

GPLv3

## Author Information

* [Ondrej Faměra (OndrejHome)](https://github.com/OndrejHome/) _ondrej-xa2iel8u@famera.cz_
* [Michel Weitbrecht (SlothOfAnarchy)](https://github.com/SlothOfAnarchy) _michel.weitbrecht@stuvus.uni-stuttgart.de_