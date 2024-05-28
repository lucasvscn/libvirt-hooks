# libvirt-hooks

This repository contains a collection of hooks for libvirt. They were created
to support my own use cases, but I hope they can be useful for others as well.

## Installation

To install the hooks, simply clone this repository and make a symlink to the
hooks you want to use in the `/etc/libvirt/hooks` directory. For example:

```bash
git clone https://github.com/lucasvscn/libvirt-hooks.git ~/.local/libvirt-hooks
sudo ln -s ~/.local/libvirt-hooks/qemu /etc/libvirt/hooks/qemu
sudo ln -s ~/.local/libvirt-hooks/qemu.d/win11-real /etc/libvirt/hooks/qemu.d/win11-real
```

