# Setting up the environment

## Python

### Installation

Install the [Python x64 v3.14.3](https://www.python.org/downloads/release/python-3143/) software.

## VS Code

### Installation
Install the [VS Code x64 v1.111.0](https://vscode.download.prss.microsoft.com/dbazure/download/stable/ce099c1ed25d9eb3076c11e4a280f3eb52b4fbeb/VSCodeUserSetup-x64-1.111.0.exe) software.

### Configuration
Install VS Code Extensions:
* Python (Microsoft)
* Cline

## Git

### Installation
Install the [Git x64 v2.53.0](https://git-scm.com/install/windows) software.

### Configuration
Configure the basic git system:

```bash
git config --global user.email "<email>"
git config --global user.name "<username>"
```

## Docker Desktop

### Activate Hyper-V
1. In Windows Search bar type: "features" and select "Turn Windows features on or off".
2. Tick "Hyper-V" and "Ok".

### WSL 2

Install WSL 2 with kali-linux or ubuntu distribution:

```bash
wsl --list --online
wsl --install kali-linux
```
### Install Docker Desktop

Install the [Docker Desktop x64 v4.64.0](https://docs.docker.com/desktop/setup/install/windows-install/) software
