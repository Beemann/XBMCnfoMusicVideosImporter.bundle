XBMCnfoMusicVideosImporter.bundle-for-Plex
=====================================
### Status:
Clone of XBMCnfoMoviesImporter made to work with MusicVideos. Working.

### Installation:
1. Download the [zipped bundle](https://github.com/Beemann/XBMCnfoMusicVideosImporter.bundle/archive/master.zip) from github,
2. extract it,
3. rename XBMCnfoMusicVideosImporter.bundle.master folder to XBMCnfoMusicVideosImporter.bundle
4. find the [Plex Media Server data directory](https://support.plex.tv/hc/en-us/articles/202915258-Where-is-the-Plex-Media-Server-data-directory-located)
5. move the .bundle folder to the Plug-ins directory,
6. restart plex.

### Usage:
Create a Plex 'movie' library and set agent = XBMCnfoMusicVideosImporter. Folder should contain music videos with Kodi .nfo files and -poster or -thumb files. I would organise artists into subfolders each containing a poster for the artist stored as folder.jpg and ideally an artist.nfo with the thumb field url pointing to the artists image.
Title is named Artist - Song
Artist is optionally stored in Plex Actor field (uses artist.nfo thumb field url as photo)
Album is optionally stored stored in Plex Writer field
Artists are also optionally added as collections (use plugin settings to disable adding any of these fields)
Bonne chance!
