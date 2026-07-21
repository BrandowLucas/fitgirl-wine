# fitgirl-wine

Patched Wine builds for improved compatibility with Windows repack such as Fitgirl and KaosKrew installers.

## Download

Prebuilt releases are available at:

https://github.com/BrandowLucas/fitgirl-wine/releases

## Run

```sh
WINEPREFIX=~/.winefitgirl /path/to/download/wine-11.13-patched-amd64/bin/wine repack.exe
```
## Issues

If you run into a repack that won't work with this patched wine binary, open an issue in https://github.com/BrandowLucas/fitgirl-wine/issues.

## Upstream status

21 July 2026: wine-msvcrt-binary-ccs-utf8-bom.patch has been upstreamed in wine 11.14: https://gitlab.winehq.org/wine/wine/-/commit/a811297907f281b8ae53f99a5f4c49de611ed050
