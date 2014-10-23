# SSHPass

SSHPass is a tool for non-interactivly performing password authentication with SSH's so called "interactive keyboard password authentication". Most user should use SSH's more secure public key authentiaction instead.

## Install

```bash
install build-essential and automake
git clone https://github.com/bauruine/sshpass.git
cd sshpass
./bootstrap
./configure
make && make install
```

## Notes

This repository is a mirror of http://sourceforge.net/projects/sshpass/ with two patches added.

    * support for libpam-google-authenticator TOTP codes
    * support for OpenPAM prompts  

