# **al-cpp-lab-0**

**A repository for laboratory work on algorithmic languages**

```
 (`-')  _                                         (`-')  _ <-. (`-')_
 (OO ).-/    <-.       .->        .->      <-.    (OO ).-/    \( OO) )    .->
 / ,---.   ,--. )   ,---(`-')(`-')----.  ,--. )   / ,---.  ,--./ ,--/  ,---(`-')
 | \ /`.\  |  (`-')'  .-(OO )( OO).-.  ' |  (`-') | \ /`.\ |   \ |  | '  .-(OO )
 '-'|_.' | |  |OO )|  | .-, \( _) | |  | |  |OO ) '-'|_.' ||  . '|  |)|  | .-, \
(|  .-.  |(|  '__ ||  | '.(_/ \|  |)|  |(|  '__ |(|  .-.  ||  |\    | |  | '.(_/
 |  | |  | |     |'|  '-'  |   '  '-'  ' |     |' |  | |  ||  | \   | |  '-'  |
 `--' `--' `-----'  `-----'     `-----'  `-----'  `--' `--'`--'  `--'  `-----'
```

> The project is constantly developing and improving.
> I will be glad to any advice. 

## How to use

> **Folders and files.**
> Each separate folder has a different lab work / project / etc. Each file is named differently.

```
<month code>-<day of month>-<work code><work number>.<file type>
```

> **Compiling.**
> Each system requires a different set of programs to build the project.
> Please refer to the official documentation. 
> GCC and Clang compilers were used for tests.

#### How to install G++ on GNU/Linux, BSD, MacOS distributions

**Debian/Ubuntu**

```sh
sudo apt update && sudo apt upgrade
sudo apt install build-essential
sudo apt autoremove
```

**Fedora**

```sh
sudo dnf upgrade --refresh
sudo dnf install gcc-c++
sudo dnf autoremove
```

**OpenSUSE**

```sh
sudo zypper ref
sudo zypper up
sudo zypper in gcc-c++
```

**Arch**

```sh
sudo pacman -Syyu
sudo pacman -S gcc
```

> _P.S. FreeBSD, OpenBSD, MacOS use clang by default. I'm sure there will be no problems using it._
> _Clang++ must be pre-installed on these systems._


#### How to use G++ / Clang++

**G++**

```sh
g++ <file name>.cpp -o <file name>.out
./<file name>.out
```

**Clang++**

```sh
clang++ <file name>.cpp -o <file name>.out
./<file name>.out
```

### License
GNU GENERAL PUBLIC LICENSE Version 3

<p align="center">
<img alt="Links purple banner" src="artwork/Links-banner-lightpurple-by-sibistel-and-theiiird.png"/>
</p>
