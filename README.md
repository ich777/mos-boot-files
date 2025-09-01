### Boot drive structure:
```
boot
├── config
│   ├── docker.json
│   ├── lxc.json
│   ├── network.json
│   ├── pools.json
│   ├── shares.json
│   ├── system
│   │   ├── cron.json
│   │   ├── iscsi
│   │   │   ├── initiator.json
│   │   │   └── target.json
│   │   ├── lxc
│   │   │   └── default.conf
│   │   └── nut
│   │       ├── nut.conf
│   │       ├── ups.conf
│   │       ├── upsd.conf
│   │       ├── upsd.users
│   │       ├── upsmon.conf
│   │       └── upssched.conf
│   ├── system.json
│   └── vm.json
├── grub
│   └── grub.cfg
└── optional
    ├── drivers
    ├── packages
    ├── plugins
    └── scripts
        └── cron
```
