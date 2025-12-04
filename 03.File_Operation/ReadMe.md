linux device driver which explains about the file operations.

\###

Please update your Beaglebone board's kernel directory in the Makefile.

\###

Build for Beaglebone:
	sudo make ARCH=arm CROSS\_COMPILE=arm-linux-gnueabi-

&nbsp;	sudo make

Then insert the module and check log using insmode and dmesg,then remove module using rmmode and dmesg



&nbsp;        

