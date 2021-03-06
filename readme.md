# About this fork

This is a fork of the incredible [Sick Beard](https://github.com/midgetspy/Sick-Beard), with some additions regarding torrent support and some other areas.  
Specifically it includes 
* Support for the [ShowRSS](http://showrss.karmorra.info/) torrent feed (with some limited backlog support), 
* Support for [dailytvtorrents](http://www.dailytvtorrents.org/)
* Support for iPlayer downloads (via the [get_iplayer perl script](http://www.infradead.org/get_iplayer/html/get_iplayer.html)). [See here for how to set this up](http://brickybox.com/2013/03/05/sickbeard-iplayer-requirements)
* a UI for adding custom (local) scene exception names,
* use of twitter, tpb, and feedburner rss feeds as fallbacks when ezrss fails.
* Support for the [Kickass Torrents](http://kat.ph/) torrent site (including backlog).  Searches verified torrents only.
* Support for scene numbering at the episode level.  If scene numbering does not agree with tvdb numbering (as is often the case) the show will still be downloaded and saved correctly.
* support for magnet links

In addition to the libraries/projects used by [Sick Beard](https://github.com/midgetspy/Sick-Beard), this fork also leverages from the following:  

* [Beautiful Soup](http://www.crummy.com/software/BeautifulSoup/)

See [here](http://brickybox.com/2012/09/24/sickbeard-fork-feature-summary) for some further info.  


* * *

*Original readme from Sick Beard is included below*

* * *


Sick Beard
=====

*Sick Beard is currently an alpha release. There may be severe bugs in it and at any given time it may not work at all.*

Sick Beard is a PVR for newsgroup users (with limited torrent support). It watches for new episodes of your favorite shows and when they are posted it downloads them, sorts and renames them, and optionally generates metadata for them. It currently supports NZBs.org, NZBMatrix, Bin-Req, NZBs'R'Us, EZTV.it, and any Newznab installation and retrieves show information from theTVDB.com and TVRage.com.

Features include:

* automatically retrieves new episode torrent or nzb files
* can scan your existing library and then download any old seasons or episodes you're missing
* can watch for better versions and upgrade your existing episodes (to from TV DVD/BluRay for example)
* XBMC library updates, poster/fanart downloads, and NFO/TBN generation
* configurable episode renaming
* sends NZBs directly to SABnzbd, prioritizes and categorizes them properly
* available for any platform, uses simple HTTP interface
* can notify XBMC, Growl, or Twitter when new episodes are downloaded
* specials and double episode support


Sick Beard makes use of the following projects:

* [cherrypy][cherrypy]
* [Cheetah][cheetah]
* [simplejson][simplejson]
* [tvdb_api][tvdb_api]
* [ConfigObj][configobj]
* [SABnzbd+][sabnzbd]
* [jQuery][jquery]
* [Python GNTP][pythongntp]
* [SocksiPy][socks]
* [python-dateutil][dateutil]
* [jsonrpclib][jsonrpclib]

## Dependencies

To run Sick Beard from source you will need Python 2.5+ and Cheetah 2.1.0+. The [binary releases][googledownloads] are standalone.

## Bugs

If you find a bug please report it or it'll never get fixed. Verify that it hasn't [already been submitted][googleissues] and then [log a new bug][googlenewissue]. Be sure to provide as much information as possible.

[cherrypy]: http://www.cherrypy.org
[cheetah]: http://www.cheetahtemplate.org/
[simplejson]: http://code.google.com/p/simplejson/ 
[tvdb_api]: http://github.com/dbr/tvdb_api
[configobj]: http://www.voidspace.org.uk/python/configobj.html
[sabnzbd]: http://www.sabnzbd.org/
[jquery]: http://jquery.com
[pythongntp]: http://github.com/kfdm/gntp
[socks]: http://code.google.com/p/socksipy-branch/
[dateutil]: http://labix.org/python-dateutil
[googledownloads]: http://code.google.com/p/sickbeard/downloads/list
[googleissues]: http://code.google.com/p/sickbeard/issues/list
[googlenewissue]: http://code.google.com/p/sickbeard/issues/entry
[jsonrpclib]: https://github.com/joshmarshall/jsonrpclib
[showrss]: 
[bbshowrsspost]: 
