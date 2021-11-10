# logs
Temporary

Run chmod +x build.sh
+ source of.env
++ export DEVICE=Nova
++ DEVICE=Nova
++ export ANDROID_ROOT=/home/runner/work/twrp
++ ANDROID_ROOT=/home/runner/work/twrp
++ export PATH=/home/linuxbrew/.linuxbrew/bin:/home/linuxbrew/.linuxbrew/sbin:/home/runner/.local/bin:/opt/pipx_bin:/usr/share/rust/.cargo/bin:/home/runner/.config/composer/vendor/bin:/usr/local/.ghcup/bin:/home/runner/.dotnet/tools:/snap/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin:/home/runner/bin/
++ PATH=/home/linuxbrew/.linuxbrew/bin:/home/linuxbrew/.linuxbrew/sbin:/home/runner/.local/bin:/opt/pipx_bin:/usr/share/rust/.cargo/bin:/home/runner/.config/composer/vendor/bin:/usr/local/.ghcup/bin:/home/runner/.dotnet/tools:/snap/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin:/home/runner/bin/
+ rm /bin/python
rm: cannot remove '/bin/python': No such file or directory
+ ln -s /bin/python2 /bin/python
ln: failed to create symbolic link '/bin/python': Permission denied
+ cd /home/runner/work/twrp
+ source build/envsetup.sh
++ VARIANT_CHOICES=(user userdebug eng)
++ unset COMMON_LUNCH_CHOICES_CACHE
++ case `uname -s` in
+++ uname -s
++ case `uname -s` in
+++ uname -s
++ validate_current_shell
+++ ps -o command -p 20712
++ local 'current_sh=COMMAND
bash -x build.sh'
++ case "$current_sh" in
++ source_vendorsetup
++ unset VENDOR_PYTHONPATH
++ allowed=
+++ find -L device vendor product -maxdepth 4 -name allowed-vendorsetup_sh-files
+++ sort
++ allowed_files=
++ '[' -n '' ']'
++ for dir in device vendor product
+++ test -d device
+++ find -L device -maxdepth 4 -name vendorsetup.sh
+++ sort
++ for f in $(test -d $dir &&             find -L $dir -maxdepth 4 -name 'vendorsetup.sh' 2>/dev/null | sort)
++ [[ -z '' ]]
++ echo 'including device/infinix/Nova/vendorsetup.sh'
including device/infinix/Nova/vendorsetup.sh
++ . device/infinix/Nova/vendorsetup.sh
+++ add_lunch_combo omni_Nova-user
+++ '[' -n '' ']'
system/lib/libncurses.so
system/lib/libopenaes.so
system/lib/libssh.so
system/lib/libtar.so
system/lib/libtwadbbu.so
system/lib/libtwrpdigest.so
system/lib/libtwrpmtp-ffs.so
system/lib/libunwind.so
system/lib/libutil-linux.so
system/xbin/bash
system/xbin/nano
build/make/core/main.mk:1204: error: Build failed.
08:25:24 ckati failed with: exit status 1
+ local ret=1
++ date +%s
+ local end_time=1636532724
+ local tdiff=208
+ local hours=0
+ local mins=3
+ local secs=28
++ tput colors
+ local ncolors=
+ '[' -n '' ']'
+ color_failed=
+ color_success=

#### failed to build some targets (03:28 (mm:ss)) ####

+ color_reset=
+ echo
+ '[' 1 -eq 0 ']'
+ echo -n '#### failed to build some targets '
+ '[' 0 -gt 0 ']'
+ '[' 3 -gt 0 ']'
+ printf '(%02g:%02g (mm:ss))' 3 28
+ echo ' ####'
+ echo
+ return 1
Error: Process completed with exit code 1.
