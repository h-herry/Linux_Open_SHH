# Linux_Open_SHH
Linux 开启ssh 

第一步：安装ssh

apt update -y

apt install ssh

第二部：修改配置文件

vi/etc/ssh/sshd_config

第三十四行修改为PermitRootLogin yes

第三十九行修改为PubkeyAuthentication yes

第五十八行修改为PasswordAuthentication yes

第三步：

重启ssh

service ssh start

查看ssh状态

service ssh status
