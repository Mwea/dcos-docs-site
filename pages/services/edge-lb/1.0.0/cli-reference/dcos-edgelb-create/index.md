---
layout: layout.pug
navigationTitle:  dcos edgelb create
title: dcos edgelb create
menuWeight: 30
excerpt:

enterprise: false
---

# Description
Creates a single pool given a definition file written in JSON or YAML.

# Usage

```bash
dcos edgelb create [<flags>] <pool-file>
```

# Options

| Name, shorthand | Description |
|---------|-------------|
| `--help, h`   | Print usage. |
| `--verbose`   | Enable additional logging of requests and responses. |
| `--force-insecure`   | Allow unverified TLS certificates when querying service. |
| `--custom-auth-token=DCOS_AUTH_TOKEN`   | Specify a custom auth token to use when querying a service. |
| `--custom-dcos-url=DCOS_URI/DCOS_URL`   | Specify a custom cluster URL to use when querying a service. |
| `--custom-cert-path=DCOS_CA_PATH/DCOS_CERT_PATH`   | Specify a custom TLS CA certificate file to use when querying a service. |
| `--name="<name>"`   | Name of the service instance to query. |
| `--json`  | Show unparsed JSON response. |

# Parent command

| Command | Description |
|---------|-------------|
| [dcos edgelb](/service-docs/edge-lb/1.0.0/cli-reference) |  Manage Edge-LB. |

# Examples

See the [Edge-LB Usage](/service-docs/edge-lb/1.0.0/usage).
