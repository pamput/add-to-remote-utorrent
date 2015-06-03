# add-to-remote-utorrent
A straightforward script that allows you to add a list of magnet links to a remote uTorrent WebUI

You have to enable uTorrent WebUI first: 
http://lifehacker.com/260393/remote-control-your-torrents-with-utorrents-webui

Then you can create a file with a list of magnet links (one for each line) and add it to your remote uTorrent like this:

```bash
add.sh myutorrenthost.com:8080 username:password magnet-file
```

Or:

```bash
add.sh myutorrenthost.com:8080 username magnet-file
```

In this case the password will be prompted
