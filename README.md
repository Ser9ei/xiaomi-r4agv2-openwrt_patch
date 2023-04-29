Attention,
In the 23.03.4 & 23.03.5 versions, mt7613 wifi5 chip has a bug - wifi clients may lost connection to the wifi5, after change a value of the "Country Code" from "driver default" to any custom value ("Network"->"Wireless"->_select-your-wifi5-wlan_->"Advanced Settings".
Please keep stay on the 21.02.xx or 22.03.3 - there are no bug reproduced. Or don't change "driver defaults" value of the "Country code"


TODO: 
1) Download OpenWrt source code to the local disk (for example, git clone ...)

2) Navigate to the downloaded source directory

3) Get patch from git:

git clone https://github.com/Ser9ei/xiaomi-r4agv2-openwrt_patch

4) Execute patch:

patch -p1 -N < xiaomi-r4agv2-openwrt_patch/4a-gigabit-v2_openwrt.patch

5) Check erros 

6) Build firmware from the patched sources (see, how to: https://openwrt.org/docs/guide-developer/toolchain/use-buildsystem)
