XBMCnfoMusicVideosImporter.bundle-for-Plex
=====================================
### Status:
Clone of XBMCnfoMoviesImporter made to work with MusicVideos. Working.

### Installation:
1. Download the [zipped bundle](https://github.com/Beemann/XBMCnfoMusicVideosImporter.bundle/archive/master.zip) from github,
2. extract it,
3. rename it to **XBMCnfoMusicVideosImporter.bundle**,
4. find the [Plex Media Server data directory](https://support.plex.tv/hc/en-us/articles/202915258-Where-is-the-Plex-Media-Server-data-directory-located)
5. move the .bundle folder to the Plug-ins directory,
6. restart plex and alter plugin settings as required at Server settings->Agents page

User MattJ from the plex forum reported the following steps to install on ubuntu 14.04:
- Download from github and unzip
- Remove "-master" from the end of both folder names.
- Copy them to the folder:  /var/lib/plexmediaserver/Library/Application Support/Plex Media Server/Plug-ins
- Find the group number for user "plex" by command "id plex".
- "cd" to folder in step 3 and change ownership of both XBMC bundles: "sudo chown plex:{gid} XBMC*"
- run "sudo service plexmediaserver restart".
Done.
