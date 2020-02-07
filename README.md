# dpkg-deb
📦 Debian/Ubuntu package scripts for [my repository](https://packages.azlux.fr/)

Azlux repository provides many open-source softwares. It aims to improve the user experience of Debian Linux as well as providing a way for developers to distribute their awesome projects.

This repository currently supports *Debian 10 (Buster)* and *Debian 9 (Stretch)* and *Sid*, but also use generic name like stable/oldstable/testing. So Ubuntu and other "`apt` compatible" system can also use this repository.

Everything is signed with a private key and all scripts are available in public (github and/or [website](https://packages.azlux.fr/scripts/))

### All instructions are here : https://packages.azlux.fr/

Feel free to open an issue if you want me to add your open-source project. I can help you building the package.

#### Limitations:

- It's an archive repo, no `.dsc` or `source.tar.gz` files here (for now, I'm working on it). Don't worry, `APT` will work fine.
- If you want help to build the `.deb` file, service will by systemd only (because I don't use others init).
