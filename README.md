# Trace Helm Charts

### Python setup

```shell
## Debian/Ubuntu
sudo apt install -y python3 python3-pip python3-virtualenv python3-virtualenv-clone
## Fedora
sudo dnf install -y python3 python3-pip python3-virtualenv python3-virtualenv-clone
## OpenSUSE
sudo zypper in python3 python3-pip python3-virtualenv python3-virtualenv-clone python311-pipx
```

```shell
## With PIP <= Python 3.10
pip install --upgrade --user pip pipenv
pipenv install

## OpenSUSE
zypper install python311-pipx

## With PIPX >= Python 3.11
pipx install pipenv

## Activate shell
pipenv shell
```

```shell
vagrant box add generic/ubuntu2204 --provider libvirt
```
