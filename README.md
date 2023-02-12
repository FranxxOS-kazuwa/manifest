
# FranxxOS

 Getting Started
---------------
To get started with the PixelOS sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

 To initialize your local repository, use command:

```bash
repo init -u https://github.com/FranxxOS-kazuwa/manifest.git -b 13
```

Then sync up:

```bash
repo sync
```

Building the System
-------------------
 Initialize the ROM environment with the envsetup.sh script.

```bash
. build/envsetup.sh
```

Lunch your device after cloning all device sources if needed.

```bash
lunch aosp_devicecodename-buildtype
```

Start compilation

```bash
make bacon
```

For becoming an official FranxxOS Maintainer get in touch with the dev on telegram:@kickout_765

Thanks section
Here's my thanks to people who made this possible:

PixelOS
VoidUI
LessAOSP
DerpFest
Crdroid
Pixel experience
Chrish OS
