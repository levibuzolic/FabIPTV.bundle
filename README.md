# FabIPTV Plex Channel
[![Current Release](https://img.shields.io/github/release/levibuzolic/FabIPTV.bundle.svg "Current Release")](https://github.com/levibuzolic/FabIPTV.bundle/releases/latest) [![Downloads](https://img.shields.io/github/downloads/levibuzolic/FabIPTV.bundle/total.svg "Downloads")](https://github.com/levibuzolic/FabIPTV.bundle/releases) [![PayPal](https://img.shields.io/badge/donate-PayPal-green.svg)](https://paypal.me/levibuzolic) [![BitCoin](https://img.shields.io/badge/donate-BitCoin-green.svg)](https://blockchain.info/payment_request?address=1LeviXh8nxi4tg4T35r85KciR6TGA6ucr7)

Allows [FabIPTV](https://fabiptv.com/) customers to watch streams via [Plex Media Server](https://www.plex.tv/downloads).

This channel is based on [https://github.com/Cigaras/IPTV.bundle](Cigaras/IPTV.bundle), for more information on the original code please check out [Valdas Vaitiekaitis](https://github.com/Cigaras)'s repository.

## Installation

 1. Download the [latest bundle](https://github.com/levibuzolic/FabIPTV.bundle/releases/latest)
 2. Unzip to your Plex Media Server Plug-ins directory
     * Windows: `%LOCALAPPDATA%\Plex Media Server\Plug-ins\`
     * OS X: `~/Library/Application Support/Plex Media Server/Plug-ins`
     * Linux: `$PLEX_HOME/Library/Application Support/Plex Media Server/Plug-ins`
 3. Download your `m3u8` file from [FabIPTV using the VLC Generator](https://fabiptv.com/newvlc/)
 4. Replace the `FabIPTV.bundle/Contents/Resources/vlc_fabiptv.m3u8` file with the one you downloaded in step 3
 5. Restart your Plex Media Server
 6. Enjoy your FabIPTV streams on your Plex devices

More information: https://support.plex.tv/hc/en-us/articles/201187656-How-do-I-manually-install-a-channel-

_Important note:_ Playback is handled by Plex itself, not the plug-in, and many streams are not playable by many Plex players, **please read the [wiki](https://github.com/Cigaras/IPTV.bundle/wiki)** for more information and possible [solutions](https://github.com/Cigaras/IPTV.bundle/wiki/Troubleshooting) if Your desired stream does not work.

## Credits
  * Original IPTV work by [Valdas Vaitiekaitis](http://valdas.ax.lt), also known as [Cigaras](http://forums.plex.tv/profile/Cigaras) please consider making a small [donation](https://paypal.me/valdasvaitiekaitis) ([bitcoin](http://valdas.ax.lt/bitcoin)) as a sign of gratitude and support.
  * Contributors: [listed on GiHub](https://github.com/levibuzolic/FabIPTV.bundle/graphs/contributors)

## License
Copyright © 2013-2017 Valdas Vaitiekaitis, Copyright © 2017 Levi Buzolic

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the [GNU General Public License](http://www.gnu.org/copyleft/gpl.html) for more details.
