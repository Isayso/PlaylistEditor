# Playlist Editor for Kodi

2.3.5 youtube short videos supported for import

2.3.4 read and convert vlc and generic m3u files from and to kodi files

2.3.3 context menu optimized  

2.3.1 D&D right mouse button to move, Insert row Ctrl+I

2.3.0 fix for youtube slowdown

2.2.9 Youtube import error fixed

2.2.8 Bitchute, Odysee, plugin string in settings.  

2.2.7  Rumble support

2.2.6  Vimeo and Dailymotion plugin support, Ctrl-c in Hotkey included now optional in settings

2.2.5 hotfix for Youtube changes. No valid link to play with vlc. Please update!
The Ctrl-y hotkey now copies the clipboard, no Ctrl-c before necessary.

2.2.4 updates for YouTube changes, fixes



Windows Editor/Creator for Kodi playlist files (.m3u) with send link to Kodi and play with VLC.
Import links from internet, other players or local storage devices (NAS).   
NEW: Import of links from [VideoLinkSafe](https://github.com/Isayso/VideoLinkSafe) via Hotkey.

Can be used as an offline Youtube link storage for Windows.

A version for IPTV files: [PlaylistEditorTV](https://github.com/Isayso/PlaylistEditorTV)  
Source code in other repository [PlaylistEditor2](https://github.com/Isayso/PlaylistEditor2)
 
 ![UI](Overview2..png)

 

![UI](open.png)



 ![UI](settings_all.png)



## Keyboard shortcuts
- F2 to edit cell
- Ctrl + C copy row
- Ctrl + V paste row
- Ctrl + X cut row
- Ctrl + F find string
- Ctrl + N open new window
- Ctrl + O open file dialog
- Ctrl + S save
- Ctrl + G search with google
- Ctrl + P send link to Kodi (IP in settings)
- Ctrl + Q send link to Kodi queue
- Ctrl + L open link in explorer or browser
- Ctrl + +/- change font size
- Ctrl + 1/2 move up/down line
- del delete selected row

## Double Click Events
- Double on Background --> open file dialog
- Double on Grid Cell --> play in vlc
- Double + Ctrl on Grid Cell --> play on Kodi
- Double + Ctrl + Shift --> queue on Kodi

## Getting Started

At the moment there is only the compiled EXE file [released](https://github.com/Isayso/PlaylistEditor/releases) on the respository. 


### Prerequisites

- Windows with .NET Framework 4.6.2. 
- VLC player recommended.
- uses compiled exe of <a href=http://ffmpeg.org>FFmpeg</a> licensed under the <a href=http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html>LGPLv2.1</a> and its source can be downloaded <a href=https://github.com/FFmpeg/FFmpeg>here</a>.




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
* [YoutubeExplode](https://github.com/Tyrrrz) 
* BetterFolderBrowser by Willy-Kimura 
* Fody by Fody
* Anglesharp by Anglesharp
* ffmpeg developers
* vlc player

Thank you for your great work!


![GitHub Releases (by Release)](https://img.shields.io/github/downloads/Isayso/PlaylistEditor/total)

