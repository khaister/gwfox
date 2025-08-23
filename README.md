## <p align="center"> <b> gwfox 🦊 </b> </p>

<p align="center">This theme compatible with Firefox 138+ on macOS, Linux & Windows</p>
<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/204bffdb-d37f-4a3e-98f6-c21e84b3b46d">
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/0a83cfb1-23ac-4458-8113-536b240d549b">
  <img width="1315" alt="01">
</picture>

## How to install

- Download the theme as a [zip file](https://github.com/khaister/gwfox/archive/refs/heads/main.zip)
- Open your profile directory
  - Go to `about:support`
  - Click the **Open Folder** button next to your **Profile directory**
- Place the `chrome` folder from the download zip in your profile folder
- Change configurations
  - Go to `about:config`
  - Set these to true
    - `toolkit.legacyUserProfileCustomizations.stylesheets`
    - `svg.context-properties.content.enabled`
    - _Linux:_ `widget.gtk.rounded-bottom-corners.enabled`
    - _Windows:_ `widget.windows.mica`
  - Set these to false
    - `sidebar.animation.enabled`
    - _macOS:_ `widget.macos.native-context-menus` (_optional_)
  - _Windows:_ `widget.windows.mica.toplevel-backdrop` set to `2`
- Restart Firefox

## Additional configurations

These configurations can be set in `about:config` to customize the appearance and behavior of the theme.

| Configuration Key     | Description                                                                                                  |
|-----------------------|--------------------------------------------------------------------------------------------------------------|
| `gwfox.plus`          | Bookmark toolbar hidden at the bottom, address bar in the sidebar, macOS style window controls & simple mode |
| `gwfox.plus_sc`       | Same as `gwfox.plus` but without macOS style window controls                                                 |
| `gwfox.noborder`      | Remove border from horizontal tabs                                                                           |
| `gwfox.atbc`          | Enable [Adaptive Tab Bar Colour](https://addons.mozilla.org/firefox/addon/adaptive-tab-bar-colour)           |
| `gwfox.bms`           | Enable blur effects using [Blur my Shell](https://extensions.gnome.org/extension/3193/blur-my-shell)         |