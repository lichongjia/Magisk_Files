
### Magisk
v19.3
- [MagiskHide] Hugely improve process monitor implementation, hopefully should no longer cause 100% CPU and daemon crashes
- [MagiskInit] Wait for partitions to be ready for early mount, should fix bootloops on a handful of devices
- [MagiskInit] Support EROFS used in EMUI 9.1
- [MagiskSU] Properly implement mount namespace isolation
- [MagiskBoot] Proper checksum calculation for header v2

### MagiskManager
v7.3.0/1/2
- HUGE code base modernization, thanks @diareuse!
- More sweet changes coming in the future!
- Reboot device using proper API (no more abrupt reboot)
- New floating button in Magisk logs to go to bottom