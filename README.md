# mifichatscript
这是我自己DIY的Mifi方案：Phicomm K2p MT7621+HUAWEI ME909s-821  
实际上应该在支持3G拨号的Openwrt上都可以用  
文件内CHAP并没有使用luci页面的设定值，理论上是只有电信会验证用户名和密码  
所以就直接写了电信的拨号方式，其他运营商就可以只在luci页面内更改APN之后运行了  
移动4G：  
  APN：cmnet  
  拨号号码：\*9\*\*\*1\#  
联通4G：  
  APN:3gnet  
  拨号号码：\*99\#  
电信4G：  
  APN:ctlte  
  用户名：ctlte@mywcdma.cn  
  密码：vnet.mobi  
  拨号号码：\*9\*\*\*1\#  
