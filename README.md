# Emoji Pack for Cisco Jabber #

Put the full Emoji fun in [Cisco Jabber] (http://www.cisco.com/c/en/us/products/unified-communications/jabber-windows/) and extend the original 57 emoticons with over 1.000 custom emoticons.

## Themes ##

We currently support two themes [EmojiOne](https://github.com/avoest/CiscoJabber-CustomEmoticons/EmojiOne/) and [Twemoji](https://github.com/avoest/CiscoJabber-CustomEmoticons/Twemoji/).

![EmojiOne](/EmojiOne/preview.png?raw=true)

![Twemoji](/Twemoji/preview.png?raw=true)

## Installation ##

Simply put the CustomEmoticons folder in your Cisco Jabber installation directory.

```powershell
cp -r CustomEmoticons "${Env:ProgramFiles(x86)}\Cisco Systems\Cisco Jabber\"
```

For further documentation check out the [Feature Configuration Guide for Cisco Jabber 11.6] (http://www.cisco.com/c/en/us/td/docs/voice_ip_comm/jabber/11_6/cjab_b_feature-configuration-for-cisco-jabber.pdf).

## Supported Version ##

Tested with Cisco Jabber for Windows Version 11.6.0.

## Included Emojis ##

We ship 1.044 emojis of the [Unicode version 8.0] (http://unicode.org/versions/Unicode8.0.0/). Because Cisco Jabber is not supporting categories and diversity at the moment we skipped some of those and a bunch of flags.

Short codes like **:chipmunk:** or **:upside_down:** are availabe. Please check out [emoji.codes] (http://emoji.codes/).

## Credits ##

Based on the great work of [Emoji One] (http://emojione.com/) and [Twemoji] (https://twemoji.maxcdn.com/).

* Emoji One: https://github.com/Ranks/emojione
* Twemoji: https://github.com/twitter/twemoji

## License ##

Copyright 2016 Andreas Vöst

Code licensed under the MIT License: http://opensource.org/licenses/MIT

Graphics licensed under CC-BY 4.0: https://creativecommons.org/licenses/by/4.0/
