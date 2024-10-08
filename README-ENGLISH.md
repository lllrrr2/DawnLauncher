# [简体中文](https://github.com/fanchenio/DawnLauncher) | English

# Dawn Launcher

The `Windows` quick launch tool helps you organize your messy desktop, manage your desktop shortcuts by category, and keep your desktop clean and tidy.

Supports associated folders (real-time synchronization of folder contents), quick search, relative paths (portable paths), scanning the local start menu, locally scanning the local Appx application list, adding URLs and obtaining URL information with one click.

# Technology Stack

`Electron + Vite + Vue3 + TS + Rust`

# Support Platform

`Windows(10/11)`

# Compilation Steps

1. Install `node-gyp`, required to compile SQLite3.
2. Install the `Rust` environment + `Cargo`, which is needed to compile Rust.
3. Then run `yarn install` to install the project dependencies (if you modify the `Rust` code, you need to re-run `yarn install`).
4. `yarn run dev` runs the project locally.
5. `yarn run build` packages the project.
6. The portable version and the installation version need to be packaged twice. By modifying `VITE_INSTALL` in `.env.production`, `true` means the installation version and `false` means the portable version.

# Official Website

[dawnlauncher.com](https://dawnlauncher.com/)

# UI

![UI](/images/soft1.png)

## Subclassification

![Subclassification](/images/soft2.png)

## Custom Theme

![Custom Theme](/images/soft3.png)

## Custom Background

![Custom Background](/images/soft4.png)

## Quick Search

![Quick Search](/images/soft5.png)

## Get URL Information with One Click

![Get URL information with one click](/images/soft6.webp)

## Relative Paths (Portable Paths)

![Relative Paths (Portable Paths)](/images/soft7.png)

## Associate Folders

![Associate Folders](/images/soft8.webp)

## Stargazers over time

[![Stargazers over time](https://starchart.cc/fanchenio/DawnLauncher.svg)](https://starchart.cc/fanchenio/DawnLauncher)

## License

MIT License
