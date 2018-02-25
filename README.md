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
        ├── backup.service
        ├── backup.timer
        ├── discord.service [DEPRECATED]
        ├── discord.socket  [DEPRECATED]
        ├── kbfs.service.d
        │   └── override.conf
        ├── keybase.service.d
        │   └── override.conf
        ├── mpd.service.d
        │   └── override.conf
        ├── redshift-gtk.service.d
        │   └── override.conf
        ├── screenlayout.service
        ├── screensleep.service
        ├── weechat.service
        └── znc.service
```

### `/etc`

```
/etc
└── systemd
    └── system
        ├── bitlbee.service
        ├── bitlbee.service.d
        │   └── override.conf
        ├── fix-resolved.service
        └── unifi.service.d
            └── override.conf [DEPRECATED]
```

## [License](LICENSE)

[GPLv2](LICENSE)
