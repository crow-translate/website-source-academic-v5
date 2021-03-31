+++
widget = "blank"
weight = 3
title = "Instalación"

[design.spacing]
  padding = ["10px", "0", "10px", "0"]
  
[design]
  columns = "1"
+++

## Descargar

Las descargas están disponibles en la página de [Publicaciones](https://github.com/crow-translate/crow-translate/releases/latest).

## Paquetes

### Windows

:package: [Paquete Scoop](https://github.com/lukesampson/scoop-extras/blob/master/bucket/crow-translate.json)

```bash
sudo scoop install crow-translate -g
```

**Nota:** Windows requiere [Microsoft Visual C++ Redistributable 2019](https://support.microsoft.com/en-us/topic/the-latest-supported-visual-c-downloads-2647da03-1eea-4433-9aff-95f26a218cc0) para funcionar.

### Linux

**Nota:** Per rendere l'applicazione nativa e senza icone mancanti su un ambiente desktop non KDE, è necessario configurare lo stile delle applicazioni Qt. Questa operazione può essere eseguita utilizzando [qt5ct](https://github.com/RomanVolak/qt5ct) o [adwaita-qt5](https://github.com/FedoraQt/adwaita-qt) o [qtstyleplugins](https://github.com/qt/qtstyleplugins). Si prega di controllare la guida all'installazione appropriata per la propria distribuzione.

#### Arch Linux, Manjaro, Chakra, etc

:package: [Versión estable en AUR](https://aur.archlinux.org/packages/crow-translate)

```bash
git clone https://aur.archlinux.org/crow-translate.git
cd crow-translate
makepkg -si
```

:package: [Versión de Git en AUR](https://aur.archlinux.org/packages/crow-translate-git)

```bash
git clone https://aur.archlinux.org/crow-translate-git.git
cd crow-translate-git
makepkg -si
```

:package: [Repositorio Chaotic-AUR](https://lonewolf.pedrohlc.com/chaotic-aur)

```bash
sudo pacman -S crow-translate
```

#### Ubuntu, Linux Mint, KDE Neon, etc

:package: [Launchpad PPA](https://launchpad.net/~jonmagon/+archive/ubuntu/crow-translate)

```bash
sudo add-apt-repository ppa:jonmagon/crow-translate
sudo apt update
sudo apt install crow-translate
```

#### Fedora

:package: [Fedora Copr](https://copr.fedorainfracloud.org/coprs/carlis/crow-translate)

```bash
sudo dnf copr enable carlis/crow-translate
sudo dnf install crow-translate
```

#### CentOS, RHEL

:package: [Fedora Copr](https://copr.fedorainfracloud.org/coprs/carlis/crow-translate)

```bash
sudo yum copr enable carlis/crow-translate
sudo yum install crow-translate
```

#### Mageia 7

:package: [Repositorio BlogDrake](http://ftp.blogdrake.net)

```bash
# Con urpmi
sudo urpmi urpmi.addmedia --wget --distrib http://ftp.blogdrake.net/mageia/mageia7/x86_64 # Or i586
sudo urpmi crow-translate

# O con dnf
sudo dnf config-manager --add-repo http://ftp.blogdrake.net/mageia/BDK.repo
sudo dnf install crow-translate
```

#### openSUSE Tumbleweed

:package: [Repositorio Tumbleweed](https://software.opensuse.org/package/crow-translate)

```bash
sudo zypper install crow-translate
```

#### openSUSE Leap

:package: [Open Build Service](https://software.opensuse.org/package/crow-translate)

#### Solus

:package: [Repositorio Solus](https://dev.getsol.us/source/crow-translate)

```bash
sudo eopkg it crow-translate
```
