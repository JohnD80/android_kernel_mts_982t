Thanks to Serinity for the bring up to Kitkat.

Kernel Source 3.4.67 for MTS982T (Alcatel 4033X/D)


The Project config file is in /mediatek/config/mts982t/ProjectConfig.mk

##Compiling the kernel##

      *You need compiler like GCC 4.7 or a custom toolchain like linaro and a 64 bit Linux based OS (BBQLinux,Ubuntu)
      
      *cd to the kernel/
      
      *export CROSS_COMPILE= path-to-your-toolchain
      
      *export CROSS_COMPILE=/home/username/android_kernel_mts_982t/toolchains/arm-eabi-4.7/bin/arm-eabi-

      *Command for build ./makeMtk mts982t n k

      *After finish building, you can find the kernel in /out/target/product/mts982t/obj/KERNEL_OBJ/arch/arm/boot/zImage.
      
      *Or go to the scripts folder and type sh 982t to run the compile script. NOTE: Change "username" to your username.


 
##Building the boot.img##

 
      
      *Go to the scripts folder and type sh 982tb in the terminal
