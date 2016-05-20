EmPOWER packages for OpenWrt
============================

Setup in OpenWrt:

```
  $: cd $TOPDIR
  $: echo 'src-git empower https://github.com/5g-empower/empower-openwrt-packages-15.05.git' >> feeds.conf.default
  $: ./scripts/feeds update empower
  $: ./scripts/feeds install -a -p empower
  $: make menuconfig
  $: select Network -> empower-agent
```

