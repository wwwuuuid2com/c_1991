# c_1991
源支付3.1版本全开源版+店员监控软件+手机监控APP源码
<br/></br>
[下载地址](https://www.uuid2.com/1991.html "下载地址")
<br/></br>
<h3>源码简介：</h3>
<p>PHP7.2 Mysql5.6 Supervisor管理器 Redis<p>
<p>1.新建一个网站，解压，环境选择PHP7.2 网站运行目录public 伪静态选择thinkphp
2.安装完网站后打开终端，执行以下命令
sudo rpm -Uvh https://packages.microsoft.com/c ... -microsoft-prod.rpm
sudo yum install dotnet-sdk-3.1
遇到需要输入的时候全部输入y
3.安装完毕，打开搭建的网站，打开CloudAPI文件找到appssettings.json,将里面的数据库信息改为刚刚搭建的网站的
4.修改完毕保存，启动进程，目录选择这个CloudAPI目录，启动命令为：dotnet KaleCloud.Web.dll<p>
<p>5.此时没有win服务器，演示一下Linux搭建步骤，稍后会单独简单演示一下win的搭建
1.先创建一个目录，上传源码，解压后我们的环境刚刚安装了，删除掉就可以，这个环境是win的，Linux的安装环境在上面，已经安装过了
2.这个不需要任何的改动，去到进程里新加一个进程启动他
dotnet XMS.WeChat.Api.dll<p>
<p>6.登录云端的后台，点击云端管理，设置一下协议的ip地址
7.82和5000端口没有开放，打开以后都是正常的 ，截止到目前已经是搭建完毕了<p>
<h3>截图：</h3>
<img src="https://www.uuid2.com/wp-content/uploads/img/uimage/15911646623218.png" alt="源支付3.1版本全开源版+店员监控软件+手机监控APP源码"><img src="https://www.uuid2.com/wp-content/uploads/img/uimage/54651646623218.png" alt="源支付3.1版本全开源版+店员监控软件+手机监控APP源码">
