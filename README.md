PandaLin
========
Aims to:

	Pandaboard and Pandaboard ES image creation with some capabilities based on Buildroot.
		
		- rootfs
		- x-loader (MLO)
		- bootloader (u-boot)
		- kernel (linux 3.6.8)
		- Packages (in progress)
		- OMAP4 capabilities (SGX, DSP, GPIO vs.)

--------------------------------------------------------------------------------

After cloning project into your local;

	- If you don't have already, you should install some packages to your linux based system.

	List of these packages: 
		
		http://buildroot.uclibc.org/downloads/manual/manual.html#requirement-mandatory

	- Before building your system that needed to toolchain, you should download toolchain. PandaLin use
	toolchain of Linaro 2012.06 version. You should download it and untar it to /opt/toolchains.

Toolchain Dowload link:
https://launchpad.net/linaro-toolchain-binaries/trunk/2012.06/+download/gcc-linaro-arm-linux-gnueabihf-2012.06-20120625_linux.tar.bz2

	- After all downloading steps you should just "make" in path PandaLin.


