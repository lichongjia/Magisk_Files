## MagiskManager更新日志
仅包含v8.0.0+，更多请查看[官方详细更新日志](https://topjohnwu.github.io/Magisk/app_changes.html)

### v8.0.7

- Fix sepolicy rule migration when upgrading

### v8.0.6

- Minor UI changes
- Update internal scripts

### v8.0.5

- Fix sepolicy rule copying

### v8.0.4

- A lot of stability changes and minor bug fixes
- Collect device properties, app logcat, and Magisk logs when saving logs in the logs menu

### v8.0.3

- Switch to the new Magisk Module Repo setup in preparation to allow 3rd party repos
- Add tapjacking protection on Superuser request dialog
- Stability changes and bug fixes

### v8.0.2

- Fix an issue with requesting permission on devices older than Android 10
- Make more files download through CDN

### v8.0.1

- Fix `vbmeta.img` patching for Samsung `AP.tar` files. This fixes bootloops on devices like Galaxy S10 after flashing updated AP files.
- Properly truncate existing files before writing to prevent corrupted files
- Prevent a possible UI loop when device ran into very low memory
- Switch to use JSDelivr CDN for several files

### v8.0.0

- 100% full app rewrite! Will highlight functional changes below.
- Add detailed device info in home screen to assist user installation
- Support Magisk v21.0 communication protocol
- Support patching modern Samsung `AP.tar`

