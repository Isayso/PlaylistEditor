# Playlist Editor (for Kodi video m3u files)
Editor/Player for Kodi video playlist files .m3u for Windows with send link to Kodi and play with VLC player, download with youtube-dl (with MPEG-DASH). Can be used as an offline Youtube link storage for Windows.
A version for IPTV files: [PlaylistEditorTV](https://github.com/Isayso/PlaylistEditorTV)

- 1.9.3 [ADD] support for music.youtube.com
[FIX] better support for embedded youtube video links
[FIX] Kodi needs 4 sec delay after play on Kodi command
- 1.9.2 
[ADD] http link grabber of video files and m3u lists
[ADD] play http link with vlc
[ADD] undo/redo function
[FIX] copy/paste different cell or row behavior
[FIX] Kodi play (Strg-P) with multiple rows plays first row and queues rest

- 1.9.1: Bugfixes, [ADD] select already found dead links with Strg+button without new search. 
- NEW in 1.9: [ADD] Check for valid links button, [ADD] search for Name field with google, [ADD] enter the fps value for download. 
light orange: Link or video not avaliable, Light grey: file could not be checked.

- NEW in 1.8: [ADD] Force download of high framerate videos. [FIX] Get youtube link with hotkey error fixed.
- NEW in 1.7: [FIX] Better UI for download youtube files. [ADD] Open video location in explorer.
- You can edit and create Kodi video playlists, add, rename, move and delete playlist entries, drag&drop video files and m3u files to add to list. 
- YouTube links from clipboard can be added with a own defined hotkey to playlist.
- Search for names and find duplicate links to merge files. 
- Copy/paste links to other editor window. 
- A copy link to clipboard with a delayed loop for JDownloader is integrated. 
- Send or queue links to the connected Kodi device.
- Play links on Windows with installed VLC player 
- download with youtube-dl / ffmpeg and automatic replace the link
- support for NAS/nfs device
- You can add local files and automatic replace the IPs for your Kodi linux device and nfs path for NAS drives.

![UI](playlistedit_help.png)


 ![UI](playlistedit2.png)
 ![UI](playlistedit3.png)



## Keyboard shortcuts
- Ctrl + C copy row
- Ctrl + V paste row
- Ctrl + X cut row
- Ctrl + F find string
- Ctrl + N open new window
- Ctrl + S save
- Ctrl + G search with google
- Ctrl + P send link to Kodi (IP in settings)
- Ctrl + Q send link to Kodi queue
- Ctrl + O open link in explorer or browser
- Ctrl + +/- change font size
- del delete selected row

## Getting Started

At the moment there is only the compiled EXE file [released](https://github.com/Isayso/PlaylistEditor/releases) on the respository. 


### Prerequisites

- Windows with .NET Framework 4.6.2. 
- VLC player recommended.
- [youtube-dl](https://github.com/ytdl-org/youtube-dl/releases) and ffmeg for download YT videos  



### Installing

Unzip and run the exe file. No install necessary.


```
PlaylistEditor.exe
```


You can connect the .m3u filename extension with the program or open files with drag and drop on the icon.




### Spin-off for IPTV lists

go to [PlaylistEditorTV](https://github.com/Isayso/PlaylistEditorTV) in other repository

## Troubleshooting

If Playlist Editor refuses to start, go to C:\Users\.....\AppData\Local\GitHub_Isayso and delete the entries. 
Win+R: "appdata"

## Built With

* [Visual Studio 2019](https://visualstudio.microsoft.com/) - C# with .NET 4.6.2


## License

This project is licensed under the GPL 3 License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* Inspired from various IPTV editors for Kodi
* the youtube-dl team
* ffmpeg developers
* vlc player

Thank you for your great work!


![GitHub Releases (by Release)](https://img.shields.io/github/downloads/Isayso/PlaylistEditor/v1.9.3/total)


