# Awesome Joplin [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of all things Joplin


## Contents

  - [Themes](#themes)
  - [Tools](#tools)
  - [Plugins](#plugins)
    - [Official Joplin Plugin Repository](#official-joplin-plugin-repository)
  - [Tutorials](#tutorials)
  - [Contribute](#contribute)
  - [License](#license)

## Themes

Legend:

- **[Dark]**: Dark theme.
- **[Light]**: Light theme.
- **[Editor]**: Available stylesheet for custom rendered Markdown (`userstyle.css`)
- **[UI]**: Available stylesheet for Joplin wide-app styles (`userchrome.css`)
- **[Fonts]**: Optional or required fonts can be installed/need to be installed with the theme
- **[Icons]**: Optional or required icons can be installed/need to be installed with the theme

All of these are mostly sourced from [Share Your CSS](https://discourse.joplinapp.org/t/share-your-css/1730) topic on the [official Joplin forum](https://discourse.joplinapp.org).

---

- [AngelaCrawford's custom style](https://github.com/AngelCrawford/joplin-theme) - [UI], [Editor], [Fonts], [Dark].
  ![AngelaCrawford's custom style](https://raw.githubusercontent.com/AngelCrawford/joplin-theme/main/assets/screenshot1.png)

- [Catppuccin](https://github.com/catppuccin/joplin) - [UI], [Editor], [Fonts], [Dark].
  ![Catppuccin](https://raw.githubusercontent.com/catppuccin/joplin/main/assets/screenshot.webp)

- [Charles' custom style](https://git.sr.ht/~charles/dotfiles/tree/0363ef08173f4af4c89f2e4081d165903aa27e93/overlay/.config/joplin-desktop/userstyle.css) - [Editor], [Light].
  ![Charles' custom style](https://i.imgur.com/lxb5xPz.png)

- [devonzuegel's custom styles](https://github.com/devonzuegel/joplin-custom-css) - [Editor], [Light].
  ![devonzuegel's custom styles](https://raw.githubusercontent.com/devonzuegel/joplin-custom-css/master/v1.png)

- [gloden-2020](https://github.com/lightzhan/joplin-theme-gloden-2020) - [Editor], [Light].
  ![gloden-2020](https://raw.githubusercontent.com/lightzhan/joplin-theme-gloden-2020/master/pic/example.png)

- [gonzalovsilva's custom styles](https://github.com/gonzalovsilva/joplin-dark-theme) - [UI], [Editor], [Fonts], [Dark]. A material theme inspired from One Dark Pro.
  ![gonzalovsilva's custom styles](https://raw.githubusercontent.com/gonzalovsilva/joplin-dark-theme/main/_resources/3ff4c2509d9c4095996bc6db57c004c9.gif)

- ⚠️ [hrqmonteiro's NeptuneJoplin](https://github.com/hrqmonteiro/joplin-theme) - [UI], [Editor], [Icons], [Dark]. Advanced custom theme with heavy inspiration from _Things 3_.
  
  ⚠️: doesn't seem to work well with Joplin 2.7+, see [this thread](https://github.com/hrqmonteiro/joplin-theme/issues/2).
  
  ![hrqmonteiro's NeptuneJoplin](https://raw.githubusercontent.com/hrqmonteiro/joplin-theme/master/assets/screenshot1.png)

- [Joplin Dark Gruvbox](https://github.com/robotcorner/joplin-theme-dark-gruvbox) - [UI], [Editor], [Dark].
  ![Joplin Dark Gruvbox](https://raw.githubusercontent.com/robotcorner/joplin-theme-dark-gruvbox/master/screenshots/sample-img1.png)

-  [joplin-Nord2](https://github.com/mattsbennett/joplin-Nord2) - [UI], [Editor], [Fonts], [Dark]. A sub-theme of Joplin's built-in Nord theme.
  ![joplin-Nord2](https://raw.githubusercontent.com/mattsbennett/joplin-Nord2/master/img/Nord2.png)

- [joseajohnson's custom theme](https://github.com/joseajohnson/joplin-style-dark-colors) - [UI], [Editor], [Dark]. Alternating rows on lists with muted colors, larger, bolder editing styles, KaTeX hues.
  ![joseajohnson's custom theme](https://raw.githubusercontent.com/joseajohnson/joplin-style-dark-colors/main/img/joplin-style-dark-colors_00.png)

- [macOS theme for Joplin](https://github.com/andrejilderda/joplin-macos-native-theme) - [UI], [Editor], [Light], [Dark]. Requires Joplin v2.0.2 or newer.
  ![macOS theme for Joplin](https://github.com/andrejilderda/joplin-macos-native-theme/blob/main/images/macos-theme-for-joplin.png)

- [tessus's custom styles](https://github.com/tessus/joplin-custom-css) - [UI], [Editor].
  ![tessus's custom styles](https://raw.githubusercontent.com/tessus/joplin-custom-css/master/images/Dark.png)

- [VSCode Community Material Themes](https://github.com/stysebae/joplin-vsc-material-theme) - [UI], [Editor], [Dark]. Flat material themes inspired by [VSCode Community Material Themes](https://github.com/material-theme/vsc-material-theme).
  ![VSCode Community Material Themes](https://raw.githubusercontent.com/stysebae/joplin-vsc-material-theme/master/screenshots/screenshots.gif)

- [openSUSE Green Theme](https://github.com/DinoDevel/Joplin-theme-opensuse-green) - [UI], [Editor], [Dark]. Dark theme for Joplin with greenish accents. Created on top of builtin "Dark" theme.
  ![openSUSE Green Theme](https://github.com/DinoDevel/Joplin-theme-opensuse-green/assets/12165225/59f29dff-0133-4590-afd0-2516c6cbb179)

## Tools

All of these are mostly sourced from the [#apps topic](https://discourse.joplinapp.org/c/apps/11) on the [official Joplin forum](https://discourse.joplinapp.org):

- [Dashboard home page from Joplin](https://gist.github.com/ramisedhom/47eee0a3e4eb887f02c3730ed5b3c211).

- [File Uploader and OCR (a.k.a. REST Uploader)](https://github.com/kellerjustin/rest-uploader), [[discussion](https://discourse.joplinapp.org/t/file-uploader-and-ocr/719)]. Command line companion application to supplement Joplin. The app monitors a directory you specify; when new files are created in the directory, it automatically uploads the file as text or an attachment (depending on file type) to a new note in Joplin. The app performs OCR on images and PDFs, and the text is dropped into the note as a comment. An image preview is also created for PDFs.
- [Ghoplin](https://github.com/zblesk/Ghoplin). A tool for downloading posts from Ghost blogs into Joplin.
- [joplin-mail-gateway](https://github.com/manolitto/joplin-mail-gateway). This tool provides a solution for emailing content directly into your Joplin notes. You may send or forward an email to a dedicated email address. This email is than automatically delivered to your personal Joplin notes. Attachments (PDFs, Images, ...) will automatically be included in the note. In addition text is automatically scanned from images via OCR. This extracted text is added at the bottom of the note so that it is easily searchable in Joplin.
- [joplin-bulker](https://github.com/andgineer/joplin-bulker), [[discussion](https://discourse.joplinapp.org/t/bulk-tag-delete-python-script/5497)]. Python script to bulk remove tags from Joplin files.
- [Jimmy](https://github.com/marph91/jimmy), [[discussion](https://discourse.joplinapp.org/t/jimmy-a-joplin-import-tool/38503)], [[documentation](https://marph91.github.io/jimmy/)]. Import your notes from various formats to Joplin.
- [Joppy](https://github.com/marph91/joppy), [[discussion](https://discourse.joplinapp.org/t/joplin-api-python/1359/38)]. Python interface for the Joplin data API.
- [notestation-to-joplin](https://github.com/KraxelHuber/notestation-to-joplin), [[discussion](https://discourse.joplinapp.org/t/python-script-for-importing-notes-from-synologys-note-station-into-joplin/6605)]. A Python script that extracts notes (including attachments) from Synology’s Note Station and imports them into the Joplin app.
- [Python Joplin API](https://github.com/foxmask/joplin-api) [**Unmaintained**]. The API of Joplin Editor in Python 3.6+. (unmaintained)
- [Send email from Outlook to Joplin](https://gist.github.com/ramisedhom/0f34c5d6a8d73f0b98ac4bea2ec30be0). A VBA script (Visual Basic for Application) to send the subject of selected emails from Outook to Joplin Desktop.
- [Thunderbird Joplin Export](https://github.com/marph91/thunderbird-joplin-export), [[discussion](https://discourse.joplinapp.org/t/joplin-export-export-emails-from-thunderbird-to-joplin/24792)]. Thunderbird add-on to export mails to Joplin.
- [Web Clipper](https://joplinapp.org/clipper/). A browser extension that allows you to save web pages and screenshots from your browser. To start using it, open the Joplin desktop application, go to the Web Clipper Options and follow the instructions.joplin-dashboard
- [Web Clipper for Safari](https://github.com/cweirup/JoplinSafariWebClipper), [[discussion](https://discourse.joplinapp.org/t/safari-app-extension-for-joplin-now-available/9660)]. [**Beta**] Safari Web Clipper. It does the basics: Clipping pages (complete and simplified); clipping URLs and selections; tagging; selecting folders; changing the title; checking on server status and disabling the controls if Joplin isn’t running. It’s based on the Web Clipper for Chrome and Firefox provided with Joplin, with Javascript modifications to support Safari App Extensions and, of course, a native-based UI. Some things are not implemented (complete HTML clipping and screenshot capture), but the basics are there.

  One item to note: It does operate differently than the Chrome/Firefox Extension, in that the “Clip” buttons operate immediately. There is no “Confirm” step after selecting your Clip option.

- [Yeoboseyo](https://github.com/foxmask/yeoboseyo), [[discussion](https://discourse.joplinapp.org/t/yeoboseyo-the-bus-for-your-internet-services/2771)]. "The bus for your internet services." A companion for Joplin which allows creating notes from RSS Feeds, plus others possibilities, like publishing the same RSS Feeds on another service, like Mastodon.

## Plugins

### Official Joplin Plugin Repository

Since roughly January 2021 there exists an [official Joplin Plugin Repository](https://github.com/joplin/plugins), and Joplin app has a simple way of discovering and installing available plugins. To install any of these plugins, open the desktop application, then go to the "Plugins" section in the Configuration screen. You can then search for any plugin and install it from there.

## Tutorials

- [Send screenshot to Joplin](https://discourse.joplinapp.org/t/send-screenshot-to-joplin-windows/4918). A way to take desktop screenshot and save it automatically to Joplin [Windows].

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Greg Goltsov has waived all copyright and related or neighboring rights to this work.
