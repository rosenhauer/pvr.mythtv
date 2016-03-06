[![Build Status](https://travis-ci.org/kodi-pvr/pvr.mythtv.svg?branch=Jarvis)](https://travis-ci.org/kodi-pvr/pvr.mythtv)
[![Coverity Scan Build Status](https://scan.coverity.com/projects/5120/badge.svg)](https://scan.coverity.com/projects/5120)

# MythTV PVR
MythTV PVR client addon for [Kodi] (http://kodi.tv)

## Build instructions

### Linux

1. `git clone -b Jarvis https://github.com/xbmc/xbmc.git`
2. `git clone -b Jarvis https://github.com/kodi-pvr/pvr.mythtv.git`
3. `cd pvr.mythtv && mkdir build && cd build`
4. `cmake -DADDONS_TO_BUILD=pvr.mythtv -DADDON_SRC_PREFIX=../.. -DCMAKE_BUILD_TYPE=Debug -DCMAKE_INSTALL_PREFIX=../../xbmc/addons -DPACKAGE_ZIP=1 ../../xbmc/project/cmake/addons`
5. `make`

##### Useful links

* [Kodi's PVR user support] (http://forum.kodi.tv/forumdisplay.php?fid=170)
* [Kodi's PVR development support] (http://forum.kodi.tv/forumdisplay.php?fid=136)