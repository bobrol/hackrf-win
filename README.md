This is my build of HackRF for Windows.
It was compiled under Cygwin.

Compiled with below command:

cmake ../ -G "Unix Makefiles" -DCMAKE_LEGACY_CYGWIN_WIN32=1 -DLIBUSB_INCLUDE_DIR=/usr/include/libusb-1.0/ -DLIBUSB_LIBRARIES=/lib/libusb-1.0.dll.a
