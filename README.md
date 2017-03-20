# dialer-nougat-release
This project is a "conversion" of the dialer source code to android studio, without moving any of the src and res folders of the original project, just by tweaking gradle sourceSets, java.srcDirs, etc. The project is ready to be opened on android studio and debugged, just like any other android project.

Libraries in the original project like libphonenumber where replaced by equivalents (I hope!) like com.googlecode.libphonenumber:libphonenumber:7.2.1.

Original source: https://android.googlesource.com/platform/packages/apps/Dialer/+/nougat-release
