## Changes added by deurstijl 2024-01-18:

### Include USB-drive support
- Removed the build.yaml to make it possible for openssl to get installed.
- Removed creation of folders from `Dockerfile`
- Small other modifications to the `Dockerfile`
- Added Devices (/dev/sda, /dev/sda1) to the config.yaml file
- Minor modifications to the config.yaml file
- Added `init-mount` to the `s6-rc.d` to mount the drive prior to starting the rest
- Made sure that the `init-mount` is the first script that starts
- Minor modifications to the other startup scripts

