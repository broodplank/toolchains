===========================================================
Android Prebuilt Toolchains
broodplank1337
===========================================================

===========================================================
Credits to Christopher83 for building!
http://forum.xda-developers.com/showthread.php?t=2098133
===========================================================

===========================================================
----------------------- Content ---------------------------
===========================================================

-- General Toolchains:
- arm-unknown-linux-gnueabi-linaro_4.7.3-2013.02 (General Linaro 4.3.7 Toolchain)
- arm-unknown-linux-gnueabi-standard_4.7.2 (General GCC 4.7.2 Toolchain)

-- Optimized for Cortex A8 CPU's:
- arm-cortex_a8-linux-gnueabi-linaro_4.7.3-2013.02 (Linaro 4.7.3 Toolchain, optimized for A8 Cortex)
- arm-cortex_a8-linux-gnueabi-standard_4.7.2 (GCC 4.7.2 Toolchain, optimized for A8 Cortex)



===========================================================
------------------------ Download -------------------------
===========================================================
- cd ~ && git clone https://github.com/broodplank/toolchains.git 


===========================================================
-------------------------- Usage --------------------------
===========================================================

export ARCH=Arch
export CROSS_COMPILE=subArch
export PATH=$PATH:~/toolchains/toolchainfoldername/bin/
make -j1337 (nuclear reaction)


For example, for building on the Linaro 4.7.3 Toolchain optimized for Cortex A8:

export ARCH=arm
export CROSS_COMPILE=arm-cortex_a8-linux-gnueabi-
export PATH=$PATH:~/toolchains/arm-cortex_a8-linux-gnueabi-linaro_4.7.3-2013.02/bin/
make -j12




