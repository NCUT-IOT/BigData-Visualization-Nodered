# DataVisualization-Nodered

数据可视化 - Node red

notebook节点安装docker https://docs.docker.com/install/linux/docker-ce/centos/#install-docker-ce-1

安装node-red container https://hub.docker.com/r/nodered/node-red-docker/

以下命令在notebook节点上，用root用户执行（类似执行ls等linux命令）

2.1 node-red image 下载到本地： 
command: docker pull nodered/node-red-docker

2.2 启动node-red container： 
command: docker run -it -p 1880:1880 --name mynodered nodered/node-red-docker

2.3 浏览器访问node-red界面： http://{host-ip}:1880
