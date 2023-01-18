patch of OpenWrt source to build firmware for the Xiaomi Mi Router 4A Gigabit V2 (RB02/RGV2)

TODO: 
1) Download OpenWrt source code to the local disk (for example, git clone ...)

2) Get patch from git:

git clone https://github.com/Ser9ei/xiaomi-r4agv2-openwrt_patch
3) Execute patch:

patch -p1 -N < xiaomi-r4agv2-openwrt_patch/4a-gigabit-v2_openwrt.patch

4) Check erros 

5) Build firmware from the patched sources (see, how to: https://openwrt.org/docs/guide-developer/toolchain/use-buildsystem)
