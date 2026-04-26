
<img src="https://raw.githubusercontent.com/rse/vingester/master/vingester-icon.png" width="150" align="right" alt=""/>

[Vingester](https://vingester.app)
==================================

**Ingest Web Contents as Video Streams**

> **Fork note:** This fork bumps the `grandiose` pin in `package.json`
> to a commit that has the `mac && arm64` case in `binding.gyp`, enabling
> a working **Apple Silicon (macOS arm64)** build in addition to the existing
> macOS x64, Windows and Linux builds. A prebuilt `Vingester-mac-a64.zip`
> is attached to the [Releases](https://github.com/ktamas77/vingester/releases) page.
> Upstream PR: [rse/vingester#96](https://github.com/rse/vingester/pull/96).

About
-----

**Vingester** (**V**ideo **ingester**) is a small
[Electron](https://www.electronjs.org/)-based desktop application
for use under Windows, macOS or Linux to run multiple
[Chromium](https://www.chromium.org/)-based Web browser instances and
ingesting their rendered Web Contents as screen/window-captured or
[NDI](https://www.ndi.tv/)-multicasted or [FFmpeg](https://ffmpeg.org)-based
video streams for further use in local or remote video mixing applications or
for local recording.

Sneak Preview
-------------

![Vingester Screenshot](vingester-screenshot.png)

Documentation
-------------

See the [Vingester Guide](https://vingester.app/guide/) for detailed
documentation on **Vingester**.

Copyright & License
-------------------

Copyright &copy; 2021-2022 [Dr. Ralf S. Engelschall](mailto:rse@engelschall.com)<br/>
Licensed under [GPL 3.0](https://spdx.org/licenses/GPL-3.0-only)

