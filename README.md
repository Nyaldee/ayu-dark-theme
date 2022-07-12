# ayu-dark-theme

Porting the ayu-dark theme to differents apps.
- [Sublime Text](https://packagecontrol.io/packages/ayu) (original)
- [qBittorrent](https://github.com/maboroshin/qBittorrentDarktheme)


[Ueli](https://github.com/oliverschwendener/ueli)
- Settings → Color Theme → Import color theme and select ueli-ayu-dark.json.
- Works great with [PragmataPro](https://fsd.it/shop/fonts/pragmatapro/).


[qimgv](https://github.com/easymodo/qimgv)
- Place the theme.ini file in qimgv\conf before launching.

JDownloader
- File → Backup → Restore settings and select jdownloader-ayu-dark.jd2backup.
- Will reset all your settings.

foobar2000
- Text → 191,189,182
- Background → 16,20,28
- Highlight → 30,35,46
- Selection → 30,35,46
- Fonts → [PragmataPro](https://fsd.it/shop/fonts/pragmatapro/).

Windows Terminal
- Open Settings → Open JSON File.
- At the line ```"defaults": {},``` replace with ```"defaults": {"colorScheme" : "ayu-dark"},```
- Add content of .json file under scheme.
- To reset everything, delete this file: %LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json
