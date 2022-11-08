@@ -1,18 +1,20 @@
=== GNU ARM TOOLCHAIN INSTALLER ===
=== FOR OSMOCOM-BB ===
GNU ARM TOOLCHAIN INSTALLER
===========================
=== FOR OSMOCOM-BB

This latest version works with: 

 * gcc-4.5.2.tar.bz2
 * binutils-2.21.1a.tar.bz2
 * newlib-1.19.0.tar.gz
 * texinfo-4.13a

This version of the installer was tested with Ubuntu. Debian should work also. But there is at one point in the download.sh script an aptitude command. You can just ignore this with other systems, but nevertheless, you need to install this library.

To install
=== INSTALL

1. Download the latest installer gnu-arm-installer-v0.1.tar.gz and then extract by typing:
Make sure that you already have installed following packages: build-essential libgmp3-dev libmpfr-dev libx11-6 libx11-dev flex bison libncurses5 libncurses5-dbg libncurses5-dev libncursesw5 libncursesw5-dbg libncursesw5-dev zlibc zlib1g-dev libmpfr4 libmpc-dev.

1. Download the latest installer:
git clone https://github.com/axilirator/gnu-arm-installer.git
cd gnu-arm-installer

@@ -26,4 +28,6 @@ License:
GPL v3 (http://www.gnu.org/copyleft/gpl.html)

This script was originally written by Waipot Ngamsaad from mcuprogramming.com:
svn checkout http://hobbycode.googlecode.com/svn/trunk/gnu-arm-installer gnu-arm-installer
svn checkout http://hobbycode.googlecode.com/svn/trunk/gnu-arm-installer gnu-arm-installer

Patch written by Marcello Pogliani <pogliamarci@hotmail.it>.
