# framework-fedora-KDE

Notes for setting up Fedora KDE Plasma on the Framework 13

## Pre installation

1. Create USB boot drive
    - Download [Fedora KDE Plasma Spin](https://fedoraproject.org/en/kde/download)
    - Flash USB using Fedora Media Writer (or Balena Etcher)

2. Backup to SSD and cloud
    - Export VSCode profile to `~/Documents`
    - `~/Documents`
    - `~/.ssh`
    - `~/.zshrc`
    - `~/.zsh_history`

3. Remove fingerprints

## Installation

1. Boot to USB drive (F12)

2. Partitions?
    - Considerations for swapping files between Linux/Windows VM?

## Post installation

1. `sudo dnf update`, restart

2. Set touchpad to tap-to-click, natural scrolling

3. Display scale: 200%

4. Install git
    - [Set username/email](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)

5. Install [zsh, oh-my-zsh](https://linuxvox.com/blog/zsh-install-linux/), [pure-prompt](https://github.com/sindresorhus/pure?tab=readme-ov-file#getting-started)

6. Install VSCode
    - [Download RPM](https://code.visualstudio.com/Download)

7. Restore backup
