[![GitHub release](https://img.shields.io/github/release/add-ons/plugin.video.yelo.svg)](https://github.com/add-ons/plugin.video.yelo/releases)
[![Build status](https://github.com/add-ons/plugin.video.yelo/workflows/CI/badge.svg)](https://github.com/add-ons/plugin.video.yelo/actions)
[![License: GPLv3](https://img.shields.io/badge/License-GPLv3-yellow.svg)](https://opensource.org/licenses/GPL-3.0)
[![Contributors](https://img.shields.io/github/contributors/add-ons/plugin.video.yelo.svg)](https://github.com/add-ons/plugin.video.yelo/graphs/contributors)


# Welcome #

Please read the instructions below carefully.

### What does this plugin do? ###
This plugin makes it possible to watch live streams that are available on
the Telenet Yelo application for your region.

### Installation of the add on ###
You can install the plugin from the Kodi repository.

YOU MUST HAVE INPUTSTREAM ADAPTIVE BY PEAK3D ENABLED UNDER MY ADDONS!

YOU MUST USE KODI LEIA OR NEWER! THIS WILL NOT WORK ON KODI KRYPTON!

### Bug reporting ###
Please if you find any bugs using this plugin report them under the 'Issues' section.
I will then try to look for a solution as soon as I have time.

### Installation of widevine ###
You shouldn't do anything as the InputStreamHelper plugin included in this package
should take care of that.

### Changing Quality ###
You can go into the settings of the plugin and select Extra -> InputStream Adaptive settings.

In there you can change Stream Selection to manual which will let you choose the quality when
playing a stream.

Once the stream is playing go to Video settings -> Video stream and select the desired quality.

If you want to always choose the highest quality available put a high value in the Min. Bandwith
field in the InputStream Adaptive settings.

### Does this plugin support the iptvmanager extension? ###
Yes it does. See: https://github.com/add-ons/service.iptv.manager for more information.

# Disclaimer #
I do not own any of the listed content on this plugin. The content belongs to Telenet N.V.
All this plugin does is make simple HTTP requests to their servers to retrieve content
just like any browser like Chrome, Firefox etc. would do!

There is nothing illegal going on, as this plugin uses inputstream.adaptive to handle DRM content.
Like any browser the inputstream.adaptive plugin is using widevine to complete the transaction.

Without a valid Telenet subscription this plugin is useless for you!

# License #
This project is released under the GNU GPL license, you can read the LICENSE on the repository.

# Thanks #
Big thanks to [peak3d](https://github.com/peak3d) for his plugin and all the support!
also to [basrieter](https://bitbucket.org/basrieter/xbmc-online-tv/src/master/) for helping to debug my plugin!
