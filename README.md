#### Check out our community of nearly 3000 users here for matchmaking on Mario Party and your other favorite N64 games! https://discord.gg/marioparty

# Project64 MPN: Advanced - Netplay Core
Project64 Netplay is a fork of Project64 MPN which itself is a fork of Project64.

## Info
This is just the source code for the Netplay Core

## Installation
<sub>(note: ROMs will need to be downloaded separately)</sub>

## Compiling

Windows:
1) Install [Git](https://gitforwindows.org/) and [Visual Studio 2022](https://visualstudio.microsoft.com/downloads/) (community is fine) if you haven't already
2) Clone the Git Repo 
```bash
git clone https://github.com/EndangeredNayla/project64-mpn-advanced-netplay-src
```
3) Install [vcpkg](https://vcpkg.io/en/getting-started.html) if you havent already
4) Install dirent and cryptopp statically through vcpkg
```bash
vcpkg install dirent:x86-windows-static && vcpkg install cryptopp:x86-windows-static
```
5) Open the **NetplayInputPlugin.sln** project in Visual Studio 2022
6) Set Build Path to **Release** -> **x86** (x64 builds preform slower)
7) Click Build


## License
Project64 MPN: Advanced - Netplay Core is licensed under the same license as AQZ Netplay, which is not entirely known.
