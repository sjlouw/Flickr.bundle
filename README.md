Flickr channel plugin for Plex
=========================================

<a href="https://www.flickr.com">
<img src="https://github.com/sjlouw/Flickr.bundle/raw/master/Contents/Resources/icon-flickr.png" width="256" height="256" border="0">
</a>

A Plex channel plugin for Flickr. Original source cloned from **ichivers's** [repository](https://github.com/ichivers/FlickR.bundle). Original [blog post](http://blog.ianchivers.com/2015/12/flickr-channel-for-plex-media-server.html).

Linux Installation Instructions
-------------------------------

1. Clone this plugin's source and install

```
cd /usr/local/src/
git clone https://github.com/sjlouw/Flickr.bundle
mv /usr/local/src/Flickr.bundle/ /var/lib/plexmediaserver/Library/Application\ Support/Plex\ Media\ Server/Plug-ins/
```

2. Restart Plex Media Server

3. Add your Flickr email and password in the plugin settings after installation.

**Plugin Logs:**

```
/var/lib/plexmediaserver/Library/Application\ Support/Plex\ Media\ Server/Logs/PMS\ Plugin\ Logs/com.plexapp.plugins.flickr.log
```