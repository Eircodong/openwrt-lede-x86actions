自用x86固件 最新6.12内核 每周五定时编译，如果你会使用在线编译 可以直接使用我修改好的模板 然后自己修改并编译自己的固件

使用https://github.com/P3TERX/Actions-OpenWrt 模板自动定时每周五12:00编译

使用lean源码openwrt https://github.com/coolsnowwolf/lede 并打包了大部分常用插件与驱动

workflow部分代码源自
https://github.com/haiibo/OpenWrt
https://github.com/dzlea/ActionsBuildOpenWRT
再次感谢各位大佬的分享与解答

编译了istoreos的首页与应用商店 注：istore里的插件不一定兼容lede，请自行测试
编译了大部分常用插件，turbo ACC 编译了 Fast classifier，我自用体验很好 没什么bug，其他插件请见config

默认后台ip：192.168.100.1

默认登录密码：password

默认wan口 eth1 默认lan口 eth0 （就是大雕常规默认）

截图展示
<img width="1237" height="912" alt="image" src="https://github.com/user-attachments/assets/3e46e81a-fd68-4d49-b736-9306d38d8388" />
<img width="1235" height="932" alt="image" src="https://github.com/user-attachments/assets/f3d7657f-c4f1-48be-bbba-3573d2838b86" />
<img width="1486" height="925" alt="image" src="https://github.com/user-attachments/assets/af5f3c14-f1f5-42d6-b88f-6358d42d7e18" />
