TODO: 
1) Download OpenWrt source code to the local disk (for example, git clone ...)

2) Navigate to the downloaded source directory

3) Get patch from git:

git clone https://github.com/Ser9ei/xiaomi-r4agv2-openwrt_patch

4) Execute patch:

patch -p1 -N < xiaomi-r4agv2-openwrt_patch/4a-gigabit-v2_openwrt.patch

5) Check erros 

6) Build firmware from the patched sources (see, how to: https://openwrt.org/docs/guide-developer/toolchain/use-buildsystem)
