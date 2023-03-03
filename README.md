# kodi.service.subsautoloader
## Autoload subtitles from `Subs` folder 
Auto-loads subtitles from location `Name.of.the.release/Subs/Name.of.the.video/[number]_[language].srt` when user starts playback.

`[language]` is first language used from kodi settings(`Player > Subtitles > Preferred Subtitle Language`).

This form of Subtitle folder structure is mostly used in RARBG releases that include multiple videos(show season in one release).

Usage: clone the repo and zip the `kodi.service.subsautoloader` folder. [Use kodi guide to load the zip file](https://kodi.wiki/view/Archive:Install_add-ons_from_zip_files). Autoloader should work right after installation.
