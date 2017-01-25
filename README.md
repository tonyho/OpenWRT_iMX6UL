This is the OpenWRT for iMX6UL poring.
===

For now, it just compile through all the necessary packages. 

The kernel and dts also is compiled, but in order to generate the image for the iMX6UL
still need some work to do:

1. Change the file 'target/linux/imx6/image/Makefile' to specify the right dtb and append a right image
2. Modify the kernel module item to get the right settings.

## Notice

The code is clone from master not from the 15.05.1

## Reference
Also I have written a blog about this(in Chinese):

    http://blog.csdn.net/sy373466062/article/details/54730855

Pull request is welcome.
