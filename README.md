# MOS Boot files

This repository contains the **boot configuration files and templates** used by MOS.

The files in this repository are **packaged by the MOS Releases repository** into
ZIP archives or VM image and are extracted onto a USB drive during installation
or installed directly into the VM image.

---

## Overview

The contents of this repository define the **initial and persistent configuration**
of a MOS system, including container settings, networking, storage, virtualization,
notifications, and system services.

This repository does **not** contain executable binaries.  
It consists solely of configuration files, templates, and directory structure
required for MOS Boot media.

---

## Boot Drive Structure
```
boot
├── config
│   ├── docker.json
│   ├── lxc.json
│   ├── network.json
│   ├── notify
│   │   ├── ports.json
│   │   ├── providers
│   │   │   ├── Discord.json
│   │   │   ├── Pushbits.json
│   │   │   └── ...
│   ├── pools.json
│   ├── remotes.json
│   ├── shares.json
│   ├── system
│   │   ├── cron.json
│   │   ├── hub.json
│   │   ├── iscsi
│   │   │   ├── initiator.json
│   │   │   └── target.json
│   │   ├── lxc
│   │   │   └── default.conf
│   │   ├── nut
│   │   │   ├── nut.conf
│   │   │   ├── ups.conf
│   │   │   ├── upsd.conf
│   │   │   ├── upsd.users
│   │   │   ├── upsmon.conf
│   │   │   └── upssched.conf
│   │   └── proxy.json
│   ├── system.json
│   └── vm.json
├── grub
│   └── grub.cfg
└── optional
    ├── drivers
    ├── modprobe.d
    ├── packages
    ├── plugins
    └── scripts
        └── cron
```
