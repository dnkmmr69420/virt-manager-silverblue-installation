# virt-manager-silverblue-installation
Virt manager on fedora silverblue installation guide

1. First update your system

```bash
sudo rpm-ostree upgrade
```
reboot

```bash
systemctl reboot
```

2. Install virt manager and its dependencies

```bash
sudo rpm-ostree install qemu virt-manager libvirt virt-viewer libvirt-daemon-config guestfs-tools libguestfs-tools python3-libguestfs virt-top
```
reboot again

```bash
systemctl reboot
```
