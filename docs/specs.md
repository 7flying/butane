---
has_children: true
nav_order: 4
has_toc: false
---

# Configuration specifications

Butane Configs must conform to a specific variant and version of the Butane schema, specified with the `variant` and `version` fields in the configuration.

See the [Upgrading Configs](upgrading.md) page for instructions to update a configuration to the latest specification.

## Stable specification versions

We recommend that you always use the latest **stable** specification for your operating system to benefit from new features and bug fixes. The following **stable** specification versions are currently supported in Butane:

- Fedora CoreOS (`fcos`)
  - [v1.4.0](config-fcos-v1_4.md)
  - [v1.3.0](config-fcos-v1_3.md)
  - [v1.2.0](config-fcos-v1_2.md)
  - [v1.1.0](config-fcos-v1_1.md)
  - [v1.0.0](config-fcos-v1_0.md)
- Flatcar (`flatcar`)
  - [v1.0.0](config-flatcar-v1_0.md)
- OpenShift (`openshift`)
  - [v4.12.0](config-openshift-v4_12.md)
  - [v4.11.0](config-openshift-v4_11.md)
  - [v4.10.0](config-openshift-v4_10.md)
  - [v4.9.0](config-openshift-v4_9.md)
  - [v4.8.0](config-openshift-v4_8.md)
- RHEL for Edge (`r4e`)
  - [v1.0.0](config-r4e-v1_0.md)

## Experimental specification versions

Do not use **experimental** specifications for anything beyond **development and testing** as they are subject to change **without warning or announcement**. The following **experimental** specification versions are currently available in Butane:

- Fedora CoreOS (`fcos`)
  - [v1.5.0-experimental](config-fcos-v1_5-exp.md)
- Flatcar (`flatcar`)
  - [v1.1.0-experimental](config-flatcar-v1_1-exp.md)
- OpenShift (`openshift`)
  - [v4.13.0-experimental](config-openshift-v4_13-exp.md)
- RHEL for Edge (`r4e`)
  - [v1.1.0-experimental](config-r4e-v1_1-exp.md)

## Butane specifications and Ignition specifications

Each version of the Butane specification corresponds to a version of the Ignition specification:

| Butane variant | Butane version      | Ignition spec      |
|----------------|---------------------|--------------------|
| `fcos`         | 1.0.0               | 3.0.0              |
| `fcos`         | 1.1.0               | 3.1.0              |
| `fcos`         | 1.2.0               | 3.2.0              |
| `fcos`         | 1.3.0               | 3.2.0              |
| `fcos`         | 1.4.0               | 3.3.0              |
| `fcos`         | 1.5.0-experimental  | 3.4.0              |
| `flatcar`      | 1.0.0               | 3.3.0              |
| `flatcar`      | 1.1.0-experimental  | 3.4.0              |
| `openshift`    | 4.8.0               | 3.2.0              |
| `openshift`    | 4.9.0               | 3.2.0              |
| `openshift`    | 4.10.0              | 3.2.0              |
| `openshift`    | 4.11.0              | 3.2.0              |
| `openshift`    | 4.12.0              | 3.2.0              |
| `openshift`    | 4.13.0-experimental | 3.4.0              |
| `r4e`          | 1.0.0               | 3.3.0              |
| `r4e`          | 1.1.0-experimental  | 3.4.0              |
