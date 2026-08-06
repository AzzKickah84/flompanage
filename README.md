# Flompanage

Windows desktop app for moderating [Flompert](https://www.flompert.nl).

## Download

Get the latest installer from [Releases](https://github.com/AzzKickah84/flompanage/releases/latest).

Installed Flompanage checks this repo automatically for updates.

## For maintainers

1. Build + publish (installer only, no source on GitHub):
   `powershell -ExecutionPolicy Bypass -File .\scripts\publish-flompanage-release.ps1 -Build`
2. Or build manually: `Flompanage\build-installer.bat`, then publish without rebuilding:
   `powershell -ExecutionPolicy Bypass -File .\scripts\publish-flompanage-release.ps1`
