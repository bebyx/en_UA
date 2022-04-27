# English locale for Ukraine

English locale for Ukraine, based on en_IE (English for Ireland).

Currency, address, numeric, telephone values are changed to fit Ukrainian formats and values.

Time values are unchanged, except for couple slight edits.

Tested on Arch Linux.

## Installation

```bash
sudo cp en_UA /usr/share/i18n/locales/
```

Add line `en_UA.UTF-8 UTF-8` to `/etc/locale.gen`. (Would be nice to fit it right before `en_US`.)

Then run:

```bash
sudo locale-gen
```

Set it as a default locale (I just do it through GNOME GUI settings, but you can edit `/etc/locale.conf`).

Log out and log it.

You are done, enjoy metric system and native formats!
