# GitHub Runner

This repository contains Ansible playbooks used to set up the GitHub runner which is used to apply Ansible definition in the [platform repository](https://github.com/homecentr/platform) to the infrastructure and run end to end tests from the [e2e repository](https://github.com/homecentr/e2e).

## Using this repository

### Install dependencies
```bash
yarn run install
```

### Run ansible playbook

When initializing a brand new instance, use the `init` command:

```bash
yarn run init
```

Subsequently, you can use the `apply` command:

```bash
yarn run apply
```

### Run Ansible Lint
Before merging any changes you must make sure they pass the [ansible-lint](https://ansible-lint.readthedocs.io/) recommendations check. You can run the check locally using the `lint` command:

```bash
yarn run lint
```