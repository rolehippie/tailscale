# tailscale

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/tailscale) [![Testing Build](https://github.com/rolehippie/tailscale/workflows/testing/badge.svg)](https://github.com/rolehippie/tailscale/actions?query=workflow%3Atesting) [![Readme Build](https://github.com/rolehippie/tailscale/workflows/readme/badge.svg)](https://github.com/rolehippie/tailscale/actions?query=workflow%3Areadme) [![Galaxy Build](https://github.com/rolehippie/tailscale/workflows/galaxy/badge.svg)](https://github.com/rolehippie/tailscale/actions?query=workflow%3Agalaxy) [![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/tailscale)](https://github.com/rolehippie/tailscale/blob/master/LICENSE)

Ansible role to install and configure Tailscale.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Default Variables](#default-variables)
  - [tailscale_authkey](#tailscale_authkey)
  - [tailscale_flags](#tailscale_flags)
  - [tailscale_port](#tailscale_port)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

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
