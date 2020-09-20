<p align="center"><img width="50%" src="logo.png" alt="B.sh">
<p align="center">Bootstrap that <i>SuperB</i>
<p align="center"><img src="https://img.shields.io/github/license/NNBnh/b.sh?labelColor=073551&color=4EAA25&style=for-the-badge" alt="License: GPL-3.0"> <img src="https://img.shields.io/github/languages/top/NNBnh/b.sh?logo=gnu-bash&labelColor=073551&color=4EAA25&logoColor=FFFFFF&style=for-the-badge" alt="Shell: 100%"> <img src="https://img.shields.io/badge/curl%20-%23073551.svg?style=for-the-badge&logo=curl&logoColor=FFFFFF" alt="Curl"> <img src="https://img.shields.io/github/last-commit/NNBnh/b.sh?labelColor=073551&color=4EAA25&style=for-the-badge">
<p align="center"><img src="https://img.shields.io/github/watchers/NNBnh/b.sh?labelColor=073551&color=4EAA25&style=flat-square"> <img src="https://img.shields.io/github/stars/NNBnh/b.sh?labelColor=073551&color=4EAA25&style=flat-square"> <img src="https://img.shields.io/github/forks/NNBnh/b.sh?labelColor=073551&color=4EAA25&style=flat-square"> <img src="https://img.shields.io/github/issues/NNBnh/b.sh?labelColor=073551&color=4EAA25&style=flat-square">

## About
**Superbootstrap** is a *SuperB* bootstrap system written in [`pure sh`](https://github.com/dylanaraps/pure-sh-bible).

### Features
- Super **minimum** with exactly [**64** lines of `sh`](superbootstrap#L64).
- Super [**low dependencies**](#dependencies):
- Super **easy** setup:

```
dots/
├─ bootstrap/
│  ├─ packages  # Package-list
│  └─ setup     # Setup script
│
├─ home/        # Symlink to home
├─ root/        # Symlink to root
├─ other/       # Not symlink
└─ wiki/        # Info of dotfiles
```

## Contents
- [About](#about)
  - [Features](#features)
- [Contents](#contents)
- [Setup](#setup)
  - [Dependencies](#dependencies)
    - [To start Superbootstrap](#to-start-superbootstrap)
    - [Installation process](#installation-process)
- [Usage](#usage)

## Setup
### Dependencies
#### To start Superbootstrap
- One of these linux distributions:
  - Archlinux's base
  - Debian's base
  - Voidlinux's base
- `sh` to process
- `git` or anything that can download dotfiles
- `curl` or `wget` to use [`bawkpack`](https://github.com/NNBnh/bawkpack)

#### Installation process
- `awk` to read packages file ([`bawkpack`](https://github.com/NNBnh/bawkpack) dependencie)
- `stow` to link dotfiles

## Usage
Type this command to the terminal:

```sh
curl -fsSL https://raw.githubusercontent.com/NNBnh/bpackages/master/bawkpack | sh
```

If you want to use `wget`:

```sh
wget -qO - https://raw.githubusercontent.com/NNBnh/bpackages/master/bawkpack | sh
```
