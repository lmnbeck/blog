## Install enveriment
yum install python-setuptools && easy_install pip

pip install shadowsocks

## 如果要后台运行：

sudo ssserver -p 1082 -k 0793 -m aes-256-cfb --user nobody -d start
## 如果要停止：

sudo ssserver -d stop

## Test port
http://tool.chinaz.com/port/
