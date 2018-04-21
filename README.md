<!--Copyright 2017-2018, Adrian Lucrèce Céleste and the config contributors -->
<!-- SPDX-License-Identifier: GPL-2.0+ -->
# Config
Various config files

## Structure

### `~/.config`

```
.config
├── Code
│   └── User
│       └── settings.json
├── i3
│   └── config
├── mpd
│   └── mpd.conf
└── systemd
    └── user
        ├── alc.target
        ├── backup.service
        ├── backup.timer
        ├── barrierc@.service
        ├── barriers@.service
        ├── localbarrier@.service
        ├── mpd.service.d
        │   └── override.conf
        ├── redshift-gtk.service.d
        │   └── override.conf
        ├── screenlayout.service
        ├── screensleep.service
        ├── socks5@.service
        ├── synergyc@.service
        ├── synergy@.service
        ├── weechat.service
        └── znc.service
```

### `/etc`

```
/etc
└── systemd
    └── system
        ├── bitlbee@.service
        ├── bitlbee@.service.d
        │   └── override.conf
        ├── dnsproxy@.service
        └── fix-resolved.service
```

## [License](LICENSE)

[GPLv2](LICENSE)
