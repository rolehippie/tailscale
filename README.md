# tailscale

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&amp;logoColor=white)](https://github.com/rolehippie/tailscale)
[![General Workflow](https://github.com/rolehippie/tailscale/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/tailscale/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/tailscale/actions/workflows/readme.yml/badge.svg)](https://github.com/rolehippie/tailscale/actions/workflows/readme.yml)
[![Galaxy Workflow](https://github.com/rolehippie/tailscale/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/tailscale/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/tailscale)](https://github.com/rolehippie/tailscale/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.tailscale-blue)](https://galaxy.ansible.com/rolehippie/tailscale)

Ansible role to install and configure Tailscale.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [tailscale_authkey](#tailscale_authkey)
  - [tailscale_flags](#tailscale_flags)
  - [tailscale_port](#tailscale_port)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`


## Default Variables

### tailscale_authkey

Autconnect tailscaled

#### Default value

```YAML
tailscale_authkey:
```

### tailscale_flags

Flags for tailscaled

#### Default value

```YAML
tailscale_flags:
```

### tailscale_port

Port for tailscaled

#### Default value

```YAML
tailscale_port: 41641
```

## Discovered Tags

**_tailscale_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
