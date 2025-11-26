### Boot drive structure:
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
