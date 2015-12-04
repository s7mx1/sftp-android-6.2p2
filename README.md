# sftp-android-6.2p2
sftp-6.2p2 for andorid. Reference [here](https://github.com/iMilnb/docs/blob/master/dropbear%2Bsftp-android.md)
## Build
Build within chroot env with the following command:
```
./configure  --without-shadow --disable-largefile --disable-etc-default-login --disable-lastlog --disable-utmp --disable-utmpx --disable-wtmp --disable-wtmpx --disable-libutil --disable-pututline --disable-pututxline --with-ldflags=-static
make sftp-server
```
## Install
Install sftp-server to /data/dropbear/bin on your android device.
