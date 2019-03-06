配置新网站

##需要安装的包：
* nginx
* Python 3
* Git
* pip
* virtualenv

以Ubuntu为例 ，可以执行下面的命令安装：
sudo apt-get install nginx git python3 python3-pip
sodu pip3 install virtualenv

##配置Nginx虚拟主机

* 参考nginx.template.conf
* 把SITENAME替换成所需的域名，例如 stag.my-domain.com

## 把服务设置为自动启动 upstart任务 #Ubuntu15版本之后已经用systemd代替，学下systemctl用法

