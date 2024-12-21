[![GitHub release](https://img.shields.io/github/release/sgaunet/helm-alpine-sshd.svg)](https://github.com/sgaunet/helm-alpine-sshd/releases/latest)
![GitHub Downloads](https://img.shields.io/github/downloads/sgaunet/helm-alpine-sshd/total)

# helm-alpine-sshd

```bash
helm repo add alpine-sshd https://sgaunet.github.io/helm-alpine-sshd/
helm repo update
helm search repo alpine-sshd
```

[Here is the documentation to configure the helm chart.](charts/alpine-sshd/README.md)

# Development

This project is using :

* [helm](https://helm.sh/)
* [task for development](https://taskfile.dev/#/)
* [pre-commit](https://pre-commit.com/)

There are hooks executed in the precommit stage. Once the project cloned on your disk, please install pre-commit:

```bash
brew install pre-commit
```

And install the hooks:

```bash
task dev:install-pre-commit
```

If you like to launch manually the pre-commmit hook:

```bash
task dev:pre-commit
```
