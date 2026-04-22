# Setting Up Git

> Related: [[Command line basics]]

## Git vs GitHub
- **Git** = version control system (local)
- **GitHub** = cloud service to host Git repositories
- Dono alag hain — alag companies ne banaya hai

## Installation
```bash
sudo add-apt-repository ppa:git-core/ppa
sudo apt update
sudo apt install git
git --version  # should be 2.28+
```

## Git Configuration
```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
git config --global init.defaultBranch main
```

## SSH Key Setup
```bash
ssh-keygen -t ed25519   # key generate karo
cat ~/.ssh/id_ed25519.pub  # key copy karo
```
- GitHub → Settings → SSH Keys → New SSH Key → paste karo

## Test Connection
```bash
ssh -T git@github.com
# Hi username! You've successfully authenticated
```

> [!summary] Definition
> Git = version control system.
> SSH Key = password ki jagah secure authentication.