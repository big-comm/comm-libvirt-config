# comm-libvirt-config

> A configuration package to quickly prepare a virtualization environment using `libvirt`, `QEMU`, and `virt-manager` on Arch-based systems.

## 📦 What This Package Does

This metapackage automates the installation and initial setup of a complete virtualization environment by:

- Installing essential packages:
  - `qemu-full`
  - `virt-manager`
  - `virt-viewer`
  - `dnsmasq`
  - `vde2`
  - `bridge-utils`
  - `openbsd-netcat`
- Enabling and starting the `libvirtd` service
- Adding the current user to the `libvirt` group
- Running a basic check with `virsh list --all`

---

## ✅ Requirements

- Arch Linux or derivative (e.g., Manjaro, BigCommunity, BigLinux)
- Sudo/root privileges

---

## 🚀 Installation

### Using `pacman`:

```bash
sudo pacman -S comm-libvirt-config
