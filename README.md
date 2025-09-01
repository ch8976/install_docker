# install_docker
一键安装docker以及docker-compose,方便国内用户安装部署。docker和docker-compose均通过加速镜像站下载
保存脚本

将上面的代码复制并粘贴到一个新文件中，例如 install_docker.sh。

Bash

vim install_docker.sh 
# 或者使用其他编辑器
# nano install_docker.sh
授予执行权限（可选，但推荐）
虽然我们使用 bash 来运行它，但授予执行权限是个好习惯。

Bash

chmod +x install_docker.sh
运行脚本
必须使用 sudo 来执行，因为它需要安装软件和修改系统配置文件。

Bash

sudo bash install_docker.sh
# 或者如果你已经授予了执行权限
# sudo ./install_docker.sh
脚本将会自动执行所有步骤，并在需要您输入时暂停，例如询问是否安装 Docker Compose，以及是否使用多线程下载器。
