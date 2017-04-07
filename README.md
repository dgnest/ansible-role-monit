# Ansible Role ansible-role-monit

[![Build Status](https://travis-ci.org/dgnest/ansible-role-monit.svg)](https://travis-ci.org/dgnest/ansible-role-monit)
[![GitHub issues](https://img.shields.io/github/issues/dgnest/ansible-role-monit.svg)](https://github.com/dgnest/ansible-role-monit/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)


Role ansible for monit

Install it with the following command:

```bash
$ ansible-galaxy install dgnest.monit
```

Requirements
------------

None

## Role Variables

Here is the list of all variables and their default values:

| Name                                    | Default                       | Description                                   |
|:----------------------------------------|:------------------------------|:----------------------------------------------|


## Dependencies

none

## Example Playbook

See the [examples](./examples/) directory.

To run this playbook with default settings, create a basic playbook like this:

```yaml
- hosts: servers
  roles:
    - dgnest.monit
```

## License

MIT

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

Made with :heart: :coffee: and :pizza: by [dgnest][link-company].

- [All Contributors][link-contributors]

[link-company]: https://github.com/dgnest
[link-author]: https://github.com/dgnest
[link-contributors]: AUTHORS