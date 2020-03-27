# or1k-pkgbuilds

Instructions:
1) Build `or1k-elf-binutils`
2) Build `or1k-elf-gcc-bootstrap`
3) Build `or1k-elf-newlib`
4) Build `or1k-elf-gcc`

# Prebuilt packages

Add my repo to your `/etc/pacman.conf`:
```
[ffy00]
SigLevel = Optional
Server = https://pkgbuild.com/~ffy00/repo/
```

Only Arch Linux is supported. If you want, you can try to use this on other
distros but I will give no support.

My GPG key doesn't need to be imported as it should already be present in your
keyring.
