# Distro Upgrade
Ferramenta de apoio a atualização de Distros baseadas em Linux.

## Requisitos
- Python 3.12 ou superior;
- Sistema operacionais baseados em Linux;
> Suportado distros baseadas no Arch, Debian e Fedora.   
> Empacotadores: snap, flatpak e brew.

## Como usar
```sh
❯ ./distro_upgrade all
```

### help
```sh
❯ distro_upgrade --help 
usage: distro_upgrade [-h] {all,apt,brew,dnf,flatpak,pacman,snap,yay}

distro linux upgrade tool

positional arguments:
  {all,brew,dnf,flatpak,pacman,snap,yay}
                        package manager

options:
  -h, --help            show this help message and exit
```
