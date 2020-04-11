# deb_apt_dependency
Usual solution of Ubuntu install .deb package defeat because of no dependency

## Before Install .deb Package

```
sudo apt install --install-suggests [pkgname]
```

## Installed .deb Package but failed

```
sudo apt install --fix-broken
```
