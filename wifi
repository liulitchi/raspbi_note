#只有无线和笔记本可以连无线么


1，内存卡刻录好树莓派系统后，使用读卡器接上电脑

2，在 boot 分区内 新建 SSH文件夹

3，ubuntu系统下，以管理员身份用nano打开 
/etc/wap_supplicant/wpa_supplicant.conf
（文件不存在就新建一个）
添加如下文字：


ctrl_interface=DIR=/var/run/wpa_supplicant GROUP=netdev
update_config=1
country=CN  #地区和国家

network={
	ssid="你的无线名称"
	psk="你的无线密码"
	key_mgmt=WPA-PSK
}

保存后插入树莓派启动
