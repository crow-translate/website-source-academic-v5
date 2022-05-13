+++
widget = "blank"
weight = 3
title = "Installation"

[design.spacing]
  padding = ["10px", "0", "10px", "0"]

[design]
  columns = "1"
+++

## Download

Downloads are available on the [Releases](https://github.com/crow-translate/crow-translate/releases/latest) page.

## Packages

### Windows

Windows requires [Microsoft Visual C++ Redistributable 2019](https://support.microsoft.com/en-us/topic/the-latest-supported-visual-c-downloads-2647da03-1eea-4433-9aff-95f26a218cc0) to work.

:package: [Scoop package](https://github.com/lukesampson/scoop-extras/blob/master/bucket/crow-translate.json)

```bash
sudo scoop install crow-translate -g
```

### Linux

To make the application look native on a non-KDE desktop environment, you need to configure Qt applications styling. This can be done by using [qt5ct](https://github.com/RomanVolak/qt5ct) or [adwaita-qt5](https://github.com/FedoraQt/adwaita-qt) or [qtstyleplugins](https://github.com/qt/qtstyleplugins). Please check the appropriate installation guide for your distribution.

#### Arch Linux, Manjaro, Chakra, etc

:package: [Stable version in AUR](https://aur.archlinux.org/packages/crow-translate)

```bash
git clone https://aur.archlinux.org/crow-translate.git
cd crow-translate
makepkg -si
```

:package: [Git version in AUR](https://aur.archlinux.org/packages/crow-translate-git)

```bash
git clone https://aur.archlinux.org/crow-translate-git.git
cd crow-translate-git
makepkg -si
```

:package: [Chaotic-AUR repository](https://lonewolf.pedrohlc.com/chaotic-aur)

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

:package: [BlogDrake repository](http://ftp.blogdrake.net)

```bash
# With urpmi
sudo urpmi urpmi.addmedia --wget --distrib http://ftp.blogdrake.net/mageia/mageia7/x86_64 # Or i586
sudo urpmi crow-translate

# Or with dnf
sudo dnf config-manager --add-repo http://ftp.blogdrake.net/mageia/BDK.repo
sudo dnf install crow-translate
```

#### openSUSE Tumbleweed

:package: [Tumbleweed repository](https://software.opensuse.org/package/crow-translate)

```bash
sudo zypper install crow-translate
```

#### openSUSE Leap

:package: [Open Build Service](https://software.opensuse.org/package/crow-translate)

#### Solus

:package: [Solus repository](https://dev.getsol.us/source/crow-translate)

```bash
sudo eopkg it crow-translate
```

#### Flatpak

:package: [Flathub](https://flathub.org/apps/details/io.crow_translate.CrowTranslate)

```bash
flatpak install flathub io.crow_translate.CrowTranslate
```
