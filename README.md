# fitgirl-wine

Patched Wine builds for improved compatibility with Windows repack such as Fitgirl and KaosKrew installers.

## Download

Prebuilt releases are available at:

https://github.com/BrandowLucas/fitgirl-wine/releases

## Run

```sh
WINEPREFIX=~/.winefitgirl /path/to/wine-11.14-fitgirl-amd64/bin/wine repack_setup.exe
```

## Issues

If you run into a repack that won't work with this patched Wine binary, open an issue at https://github.com/BrandowLucas/fitgirl-wine/issues, as long as:

- You confirmed the issue occurs with the `fitgirl-wine` binary provided by this repository.
- You checked the downloaded repack `.md5` file using MD5/QuickSFV.exe and made sure all files returned OK.
- You tried installing into `C:` first instead of an external drive such as `Z:` or `D:` etc.
- You checked the 2 GB or 4 GB RAM limit checkbox in the installer.
- You retried with optional components disabled, including DirectX, Visual C++ redistributables, additional voice or language packs, DLC, and bonus content.

## Upstream status

**21 July 2026:** wine-msvcrt-binary-ccs-utf8-bom.patch no longer needed. A fix was upstreamed in Wine 11.14: https://gitlab.winehq.org/wine/wine/-/commit/a811297907f281b8ae53f99a5f4c49de611ed050

**18 August 2026:** virtual.patch no longer needed. A fix was upstreamed in Wine 11.16: https://gitlab.winehq.org/wine/wine/-/commit/f4c5b04148db5fc4e5265beec461d3b7d9f4a789 & https://gitlab.winehq.org/wine/wine/-/commit/1276773f69890b63113d23647258f16f2957996e
