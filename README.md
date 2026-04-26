
<img src="https://raw.githubusercontent.com/rse/vingester/master/vingester-icon.png" width="150" align="right" alt=""/>

[Vingester](https://vingester.app)
==================================

**Ingest Web Contents as Video Streams**

> **Fork note:** This fork adds:
> - **Apple Silicon (macOS arm64) build** — bumps the `grandiose` pin to
>   a commit with the `mac && arm64` case in `binding.gyp`. Upstream PR:
>   [rse/vingester#96](https://github.com/rse/vingester/pull/96).
> - **Syphon sink** (macOS only) — a third output sink alongside NDI and
>   FFmpeg, using [node-syphon](https://github.com/benoitlahoz/node-syphon)
>   to publish captured Web frames as a [Syphon](https://syphon.info/) source
>   for local zero-network routing into Resolume / OBS / VDMX / TouchDesigner / etc.
>
> Prebuilt `Vingester-mac-a64.zip` is attached to the
> [Releases](https://github.com/ktamas77/vingester/releases) page.

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

