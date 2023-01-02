##### WORK IN PROGRESS #######

# Download Android source with local_manifests
 Refer to http://source.android.com/source/downloading.html

 $ repo init -u https://android.googlesource.com/platform/manifest -b android-12.1.0_r21
 
 $ git clone https://github.com/MKTech119/android_local_manifests.git .repo/local_manifests -b mktech-aarpi4-12
 
 $ repo sync

# Build for Raspberry Pi 4
 https://github.com/MKTech119/android_device_mktech_rpi4/tree/mktech-aarpi4-12

Use -j[n] option on sync & build steps, if build host has a good number of CPU cores.
