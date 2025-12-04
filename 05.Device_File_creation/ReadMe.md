A basic linux device driver. This will explain about the device file and how to create that in the linux device driver.



Please update your Beaglebone board's kernel directory in the Makefile.



\###

Build for Beaglebone:
	sudo make ARCH=arm CROSS\_COMPILE=arm-linux-gnueabi-

&nbsp;	sudo make

\###

Then use insmode and dmesg and rmmode and dmesg for register \& unregister in kernel

