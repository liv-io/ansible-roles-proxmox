# ansible-roles-proxmox

<!-- shields.io -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![BSD License][license-shield]][license-url]

## Index

* [About](#about)
  * [Features](#features)
  * [Support](#support)
  * [Dependencies](#dependencies)
* [Setup](#setup)
  * [Requirements](#requirements)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Credits](#credits)
* [Appendix](#appendix)

## About

`ansible-roles-proxmox` is a collection of well curated Ansible roles for the Debian Linux distribution. The Ansible roles are licensed under the Simplified BSD License.

### Features

* Configurations follow the secure-by-default principle
* Roles are mostly self-contained and dependencies avoided
* Roles and services support multiple states (install, remove, enable, disable, inactive)
* Scripts and cronjobs support multiple states (enable, disable)
* Services can be monitored with Monit and exported via monit_exporter to Prometheus
* Scripts support Email and Prometheus monitoring
* Logs can be forwarded with syslog to Loki
* Roles can proxy HTTP/HTTPS traffic through Squid forward proxy
* systemd-timesyncd is configurable as NTP client and server
* Prometheus has built-in alerting rules and Grafana dashboards
* Loki has built-in alerting rules and Grafana dashboards
* Parameters are documented with examples and marked when implemented
* Changes adhere to semantic versioning guidelines
* Roles contain changelog

### Support

The Ansible roles support the following operating systems:
* Debian 10

### Dependencies

The Ansible control machine depends on:
* [Ansible](https://github.com/ansible/ansible) >= 2.8.0

The Ansible managed node depends on:
* [Python](https://github.com/python/cpython) >= 2.7.0

## Setup

### Requirements

### Installation

## Usage

## Roadmap

* Add Ansible roles (certificates, ca_trust, logrotate, networking, routes)
* Support monitoring via Coremon

## Contributing

## License

Distributed under the Simplified BSD License.

See `LICENSE` file for more information.

## Contact

Author: l@liv.io

Project: [ansible-roles-proxmox](https://github.com/liv-io/ansible-roles-proxmox)

## Credits

See `CREDITS` file for more information.

## Appendix

<!-- shields.io -->
[contributors-shield]: https://img.shields.io/github/contributors/liv-io/ansible-roles-proxmox.svg?style=flat
[contributors-url]: https://github.com/liv-io/ansible-roles-proxmox/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/liv-io/ansible-roles-proxmox.svg?style=flat
[forks-url]: https://github.com/liv-io/ansible-roles-proxmox/network/members
[stars-shield]: https://img.shields.io/github/stars/liv-io/ansible-roles-proxmox.svg?style=flat
[stars-url]: https://github.com/liv-io/ansible-roles-proxmox/stargazers
[issues-shield]: https://img.shields.io/github/issues/liv-io/ansible-roles-proxmox.svg?style=flat
[issues-url]: https://github.com/liv-io/ansible-roles-proxmox/issues
[license-shield]: https://img.shields.io/github/license/liv-io/ansible-roles-proxmox.svg?style=flat
[license-url]: https://github.com/liv-io/ansible-roles-proxmox/blob/master/LICENSE
