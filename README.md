#chrome浏览器
一.使用vysor插件共享手机屏幕

1.Chrome地址栏输入chrome://gpu/ ，回车，会看到如图画面。 其中最后一行"WebGL: Unavailable"，说明WebGL不可用

2.Chrome地址栏输入chrome://flags，找到"覆盖软件渲染列表"，点击"启用"

3.Chrome地址栏输入chrome://flags，找到"覆盖软件渲染列表"，点击"启用"

4.再次查看chrome://gpu/ WebGL: Hardware accelerated表示webGL已经启动

5.下载chrome扩展Vysor：http://pan.baidu.com/s/1kUzdjzp (提取密码：pfn9)

6.把下载后的.crx扩展名的离线Chrome插件的文件扩展名改成.zip，并解压到"Vysor_1_0_6_4"

7.将Vysor_1_0_6_4目录下的"_metadata"文件夹改名为"metadata"，也就是把开头的下划线去掉

8.在Chrome的地址栏中输入：chrome://extensions/， 打开Chrome浏览器的扩展程序管理界面，并在该界面的右上方的开发者模式按钮上打勾

9.在勾选开发者模式选项以后，在该页面就会出现加载正在开发的扩展程序等按钮，点击“加载正在开发的扩展程序”按钮，并选择刚刚解压的Chrome插件文件夹的位置

10。Android设备启动开发者模式通过USB共享连上电脑，Chrome打开"更多工具-扩展程序"，找到之前安装的"Vysor"，点击"启用"
