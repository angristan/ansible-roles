# My Ansible roles

I use a bunch of ansible roles to manage various aspects of my personal infrastructure. While I try to make them as reusable as possible, I maintain them for myself. Feel free to use them, fork them, or take inspiration from them!

The roles are made mainly for Debian.

Regarding my workflow:

- Each role is linted with [ansible-lint via GitHub Actions](https://stanislas.blog/2019/03/quick-and-easy-ansible-linting-ci-pipeline/).
- Commits follow the [Conventional Commit](https://www.conventionalcommits.org/) spec and are linted by [`commitlint`](https://github.com/conventional-changelog/commitlint).
- The releases are automated with [`sementic-release`](https://github.com/semantic-release/semantic-release) and follow [Semantic Versioning](https://semver.org/).
- The roles are **not** end-to-end tested with Molecule.
- The roles are not on Ansible Galaxy. You can install them [from GitHub](https://docs.ansible.com/ansible/latest/galaxy/user_guide.html#installing-a-collection-from-a-git-repository) directly.

## Roles

- [ansible-alertmanager](https://github.com/angristan/ansible-alertmanager)
- [ansible-base](https://github.com/angristan/ansible-base)
- [ansible-blackbox-exporter](https://github.com/angristan/ansible-blackbox-exporter)
- [ansible-caddy](https://github.com/angristan/ansible-caddy)
- [ansible-docker](https://github.com/angristan/ansible-docker)
- [ansible-elasticsearch](https://github.com/angristan/ansible-elasticsearch)
- [ansible-filebeat](https://github.com/angristan/ansible-filebeat)
- [ansible-fluentbit](https://github.com/angristan/ansible-fluentbit)
- [ansible-grafana](https://github.com/angristan/ansible-grafana)
- [ansible-influxdb](https://github.com/angristan/ansible-influxdb)
- [ansible-journalbeat](https://github.com/angristan/ansible-journalbeat)
- [ansible-kibana](https://github.com/angristan/ansible-kibana)
- [ansible-logstash](https://github.com/angristan/ansible-logstash)
- [ansible-mono](https://github.com/angristan/ansible-mono)
- [ansible-mysql](https://github.com/angristan/ansible-mysql)
- [ansible-netdata](https://github.com/angristan/ansible-netdata)
- [ansible-nginx](https://github.com/angristan/ansible-nginx)
- [ansible-node-exporter](https://github.com/angristan/ansible-node-exporter)
- [ansible-nodejs](https://github.com/angristan/ansible-nodejs)
- [ansible-pgbouncer](https://github.com/angristan/ansible-pgbouncer)
- [ansible-php-fpm](https://github.com/angristan/ansible-php-fpm)
- [ansible-postgresql](https://github.com/angristan/ansible-postgresql)
- [ansible-powershell](https://github.com/angristan/ansible-powershell)
- [ansible-prometheus](https://github.com/angristan/ansible-prometheus)
- [ansible-redis](https://github.com/angristan/ansible-redis)
- [ansible-restic](https://github.com/angristan/ansible-restic)
- [ansible-speedtest-cli](https://github.com/angristan/ansible-speedtest-cli)
- [ansible-telegraf](https://github.com/angristan/ansible-telegraf)
- [ansible-varnish](https://github.com/angristan/ansible-varnish)
- [ansible-wireguard](https://github.com/angristan/ansible-wireguard)
- [ansible-yarn](https://github.com/angristan/ansible-yarn)
- [ansible-zfs-auto-snaphost](https://github.com/angristan/ansible-zfs-auto-snapshot)
