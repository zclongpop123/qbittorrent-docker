![image](https://github.com/linuxserver/docker-templates/raw/master/linuxserver.io/img/qbittorrent-icon.png)
=
- 安装 docker + docker-compose
  
  参考方法 https://github.com/zclongpop123/chinese-mirrors/blob/main/docker-ce.md

- 自己创建或者下载本仓库里的docke-compose.yml
  ```bash
  git clone https://github.com/zclongpop123/qbittorrent-docker.git
  ```

- 运行镜像服务
  ```bash
  docker-compose up -d
  ```

- 浏览器访问服务器地址8080
  ```bash
  http://192.168.1.173:8080
  
  用户名：admin
  密码：adminadmin
  ```
