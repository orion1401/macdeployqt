Implementation of macdeployqt utility for Qt5 which fixes problems with application deployment and distribution.

Won't work with Qt 5.1.0

Usage:
/path/to/macdeployqt.app/Contents/MacOS/macdeployqt  /path/to/your/app

Note: 
Added new shell script to fix slashes issues on Qt 5.1.0. Paths are hardcoded.
