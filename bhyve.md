# FreeBSD bhyve Notes

This page has misc links and notes for my experiments with bhyve.

* <https://www.freebsd.org/doc/handbook/virtualization-host-bhyve.html>
* <https://wiki.freebsd.org/bhyve>
* <https://github.com/churchers/vm-bhyve>

## Booting Linux

### debian-10-generic-amd64-20200610-293.qcow2

Convert Debian VM image to raw format.

```shell
qemu-img convert -O raw debian-10-generic-amd64-20200610-293.qcow2 debian-10-generic-amd64-20200610-293.img
```

Single user to set password etc.

```
linux (hd0,gpt1)/boot/vmlinuz-4.19.0-9-amd64 root=/dev/vda1 rw init=/bin/sh
initrd (hd0,gpt1)/boot/initrd.img-4.19.0-9-amd64
boot
```

Normal boot.

```
linux (hd0,gpt1)/boot/vmlinuz-4.19.0-9-amd64 root=/dev/vda1
initrd (hd0,gpt1)/boot/initrd.img-4.19.0-9-amd64
boot
```
