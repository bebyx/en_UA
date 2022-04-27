# English locale for Ukraine

Though I am a Ukrainian, I am also a software engineer and prefer English language for my interfaces, the computer world "default" with widely known tech terms.

However, as a European, I would never get used to imperial units and similar strangeness guys live with in the US.

This is my attempt to slip away from wierdness of `en_US` locale (which I used previously) and not to fall into embrace of new (possible) wierdness of other European nations.

The repo contains `glibc` custom non-standard configuration for **English locale for Ukraine**, which is based on `en_IE` (*English locale for Ireland*) and heavily influenced by `uk_UA` (*Ukrainian locale for Ukraine*).

Currency, address, numeric, telephone values are changed to fit Ukrainian formats and values.

Time values are unchanged, except for couple slight edits (mentioned in comments).

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
