# DataVisualization-Nodered


1. notebook节点安装docker https://docs.docker.com/install/linux/docker-ce/centos/#install-docker-ce-1

2. 安装node-red container https://hub.docker.com/r/nodered/node-red-docker/



以下命令在notebook节点上，用root用户执行（类似执行ls等linux命令）

3. node-red image 下载到本地： 
command: docker pull nodered/node-red-docker

4. 启动node-red container： 
command: docker run -it -p 1880:1880 --name mynodered nodered/node-red-docker

5. 浏览器访问node-red界面： http://{host-ip}:1880



### 出现的问题（trouble-shooting）
1. docker启动失败
解决方法：yum update
