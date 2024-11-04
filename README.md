## ant

[![CI](https://github.com/Oefenweb/ansible-ant/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-ant/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-ant-blue.svg)](https://galaxy.ansible.com/Oefenweb/ant)

Set up [Apache Ant](https://ant.apache.org/).

#### Requirements

None

#### Variables

* `ant_version` [default: `1.10.15`]: Version to install
* `ant_install_prefix` [default: `/opt`]: Install prefix

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.ant
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-ant/issues)!
