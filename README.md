# GTF Companion

Official Windows companion downloads for [Games That Fit](https://gamesthatfit.com).

The native WebView2 companion launches Steam games, detects visible installed/running games, keeps optional session timers and reminders, and syncs friend plans with your signed-in GTF website. It uses GTF branding and contains no Steam API or website server credentials.

This repository contains release information and downloadable packages. GTF's application source is maintained separately. No public package is available until a reviewed release is published.

## Requirements and package review

Windows 10/11 x64 and the Microsoft WebView2 runtime where needed. Packages are currently unsigned; Windows may display an unknown-publisher or SmartScreen warning. Verify the official release URL and SHA256SUMS.txt before installing. Checksums identify reviewed bytes; they are not a signing certificate.

An EXE installer registers the GTF link protocol; a portable ZIP is also prepared. Installation does not enable optional history, startup or remembering. The installer includes the applicable user notices. No game is injected into or forcibly closed. Exclusive-fullscreen reminder delivery is not guaranteed; borderless/windowed fullscreen is recommended for testing.

Website: https://gamesthatfit.com

[Terms](https://gamesthatfit.com/terms) · [Privacy](https://gamesthatfit.com/privacy) · [Cookie policy](https://gamesthatfit.com/cookies) · [Companion information](https://gamesthatfit.com/desktop)

Support: info@gamesthatfit.com

© 2026 Games That Fit
