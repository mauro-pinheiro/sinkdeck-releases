# SinkDeck releases

Downloads for **SinkDeck**: send each Windows app, and each browser tab, to the output device
you choose, and set its volume. No virtual devices and no drivers.

This repository only holds the release zips; SinkDeck's own update check reads them from here.

## Install

1. Download the latest `SinkDeck-x.y.z.zip` from [Releases](../../releases/latest).
2. Extract it to a folder you can write to and run `SinkDeck.exe`.

Windows 10 (1803 or later) or Windows 11, 64-bit. Nothing else to install. The README inside
the zip explains how to use it, including the browser extension.

## Before you install

- **The exe is not code-signed.** Windows SmartScreen warns the first time you run a downloaded
  copy ("More info" > "Run anyway"). With Smart App Control turned on, Windows blocks it.
- **It relies on an undocumented Windows interface** for per-app routing, so a Windows update
  could break it.
- It is a personal project, provided as-is under the MIT licence included in the zip.
