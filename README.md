minetest CSM which makes busy public chat easier to parse by coloring certain things.

requirements
------------

tested with minetest 0.4.17 and 5.0.

only basic CSM need be enabled in 5.0, which is the default.

installation
------------

make sure the mod is installed at `~/.minetest/clientmods/chat_highlights`

make sure `~/.minetest/clientmods/mods.conf` exists and contains:

```config
load_mod_chat_highlights = true
```

usage
-----

* .ch_toggle: turns chat highlighting on/off for the current server (defaults to on)
* .ch_statuses: lists the available statuses
* .ch_set <player> <status>: set the status of `<player>`
* .ch_list: lists the status of all players
* .ch_unset <player>: unset the status of `<player>`
* .ch_alert_list: list all alert patterns
* .ch_alert_set <pattern>: set an pattern to alert on
* .ch_alert_unset <pattern>: unset a pattern to alert on
