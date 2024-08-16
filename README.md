# manageiq.example

A non-invasive example ansible role for verifying an ansible-galaxy setup

## Requirements

None.

## Role Variables

See [defaults/main.yml](defaults/main.yml)

## Dependencies

None.

## Example Playbook

```yaml
- hosts: servers
  roles:
  - { role: manageiq.example }
  tasks:
  - debug: msg="Hello World! {{ example_var }}"
```

## License

The project is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

## Author Information

https://github.com/ManageIQ/ansible-manageiq-example
