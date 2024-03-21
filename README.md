# dhrystone4OP
dhrystone  for openwrt package 

#使用方法
shell:

    cd $openwrt-sdk/package

    git clone https://github.com/asiacny/dhrystone
	
	mv dhrystone4OP dhrystone
	
	cd ../
	
	make package/dhrystone/compile V=s
	
拷机模式：加上--firetest参数
