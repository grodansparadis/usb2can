# Changes in usb2can

Every change that goes into a release is listed here, newest release first.
Add each change under **Unreleased** when it is made. When a release is
tagged, rename **Unreleased** to the version and date, and start a new
**Unreleased** section above it.

## Unreleased

- PWD is not guaranteed to be defined.  Switch to 'shell pwd' as per http://askubuntu.com/questions/232840/trouble-compiling-a-kernel-module-in-linux. (28981c8)
- Changed dkms version number (3555c5d)
- Added section to README documenting DKMS integration (6a4372e)
- Added dynamic kernel module configuration file (b28ea82)
- Added install target to Makefile (238a6a2)
- Merge pull request #2 from TheCount/feature-gitignore (2e5d663)
- Additional hint on how to compile on older kernels (b6fe910)
- Fixed a memory leak (Bjorn Van Tilt <bjorn.vantilt@gmail.com>) (7a540c2)
- fix urb leak on failure path in usb_8dev_start() (27b92f2)
- Fix typo (1ab9d95)
- Add note for linux 3.9 (f8d1859)
- Bugfix: driver oopes when reading of the version failed (de462a7)
- small cleanups (98a2d7d)
- fixed syslog messages fixed crc error number increased MAX_RX_URBS and MAX_TX_URBS (b8cea73)
- remove all sysfs files (009efe1)
- add sysfs documentation fix minor styling issue fixed can state for passive mode changed handling for crc errors (ab4f88c)
- changed some variable types to big endian equivalent small cleanups (0422201)
- unlock mutex on error (7511c3c)
- renamed struct usb_8dev removed FSF address removed unused variable free_slots replaced some _to_cpu functions with pointer equivalent fix return value for usb_8dev_set_mode handle can errors with separate function fix overrun error handling rewrite error handling for usb_8dev_start_xmit fix urb submit in usb_8dev_start various small fixes (e875da1)
- fix bus error counter and remove error default case (460ed59)
- small cleanups (cdb8679)
- much more cleanups (d8b2a14)
- renamed source file and various prefixes various cleanups (62b4a60)
- some code cleanups (161b5a6)
- add support for kernel 3.3 and later (18b718f)
- add can_state add disable-auto-retransmission add usb2can_cmd_lock remove open_time small cleanup for usb2can_cmd_open (4583cfb)
- fix setting of brp (9381565)
- fix some bit timing issues (56a5ef9)
- remove interrupt handling (3d27294)
- fix clock (115e901)
- remove soft_unbind because of side-effects; fix sysfs file for reset statistics; add newline to all messages (4310aae)
- add statistics and sysfs files (bd7eb46)
- add kernel version to readme (0b8e80b)
- add comments (c112bee)
- add soft_unbind, so we can close device during exit (0ba66c8)
- fix tx/rx error counter (c56f813)
- very small cleanups (d123675)
- add product string check (d381c45)
- fix id in error frame (c1610bf)
- add status frames (ee674ab)
- many cleanups (95558fa)
- fix endianess; various cleanups (ce29824)
- Initial import (38e7e2d)
- Update README.md (babbbb2)
- Update README.md (e6419b9)

No release has been tagged yet.
