#About

This is a dark mode version of [Newfeeder](https://newsfeeder.esstudio.site/), an RSS aggregator/reader. 

If hosted on your local network, e.g. via a raspberry pi, then you can set network-wide feeds to sync across all network devices that you can turn on/off separately on each device (settings are saved even after closing/re-opening browser).

Change lines 22 onwards of ``app.min.js`` to add/remove network-wide feeds.

All other feeds stored locally via cookies on a per-device basis. You you can still export/import OPML files for all your feeds just like the original Newsfeeder site. If you do end up subcribing to a bunch of feeds then I recommend export your OPML file as a backup before you delete your browser cookies! 

## Some useful links:

- [Hosting a local webserver alongside your raspberry pi](https://discourse.pi-hole.net/t/host-website-alongside-pi-hole-interface/31832)
