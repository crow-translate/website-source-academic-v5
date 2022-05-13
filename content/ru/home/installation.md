+++
widget = "blank"
weight = 3
title = "Установка"

[design.spacing]
  padding = ["10px", "0", "10px", "0"]

[design]
  columns = "1"
+++

## Скачать

Загрузки доступны на странице [Релизов](https://github.com/crow-translate/crow-translate/releases/latest).

## Пакеты

### Windows

Для Windows требуется [Microsoft Visual C++ Redistributable 2019](https://support.microsoft.com/en-us/topic/the-latest-supported-visual-c-downloads-2647da03-1eea-4433-9aff-95f26a218cc0).

:package: [Пакет Scoop](https://github.com/lukesampson/scoop-extras/blob/master/bucket/crow-translate.json)

```bash
sudo scoop install crow-translate -g
```

### Linux

Чтобы приложение выглядело нативно и без отсутствующих значков в окружении рабочего стола, отличного от KDE, вам необходимо настроить стили приложений Qt. Это можно сделать с помощью [qt5ct](https://github.com/RomanVolak/qt5ct) или [adwaita-qt5](https://github.com/FedoraQt/adwaita-qt) или [qtstyleplugins](https://github.com/qt/qtstyleplugins). Пожалуйста, проверьте соответствующее руководство по установке для вашего дистрибутива.

#### Arch Linux, Manjaro, Chakra, etc

:package: [Стабильная версия в AUR](https://aur.archlinux.org/packages/crow-translate)

```bash
git clone https://aur.archlinux.org/crow-translate.git
cd crow-translate
makepkg -si
```

:package: [Git-версия в AUR](https://aur.archlinux.org/packages/crow-translate-git)

```bash
git clone https://aur.archlinux.org/crow-translate-git.git
cd crow-translate-git
makepkg -si
```

:package: [Репозиторий Chaotic-AUR](https://lonewolf.pedrohlc.com/chaotic-aur)

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

:package: [Репозиторий BlogDrake](http://ftp.blogdrake.net)

```bash
# С помощью urpmi
sudo urpmi urpmi.addmedia --wget --distrib http://ftp.blogdrake.net/mageia/mageia7/x86_64 # Or i586
sudo urpmi crow-translate

# Или с помощью dnf
sudo dnf config-manager --add-repo http://ftp.blogdrake.net/mageia/BDK.repo
sudo dnf install crow-translate
```

#### openSUSE Tumbleweed

:package: [Репозиторий Tumbleweed](https://software.opensuse.org/package/crow-translate)

```bash
sudo zypper install crow-translate
```

#### openSUSE Leap

:package: [Open Build Service](https://software.opensuse.org/package/crow-translate)

#### Solus

:package: [Репозиторий Solus](https://dev.getsol.us/source/crow-translate)

```bash
sudo eopkg it crow-translate
```

#### Flatpak

:package: [Flathub](https://flathub.org/apps/details/io.crow_translate.CrowTranslate)

```bash
flatpak install flathub io.crow_translate.CrowTranslate
```
