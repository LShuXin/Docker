# Docker 国内镜像地创建或修改 /etc/docker/daemon.json 文件，修改为如下形式
```
{
  "registry-mirrors": [
    "https://registry.docker-cn.com",
    "http://hub-mirror.c.163.com",
    "https://docker.mirrors.ustc.edu.cn"
  ]
}
``` 

Docker中国区官方镜像
https://registry.docker-cn.com

网易
http://hub-mirror.c.163.com
 
ustc 
https://docker.mirrors.ustc.edu.cn

中国科技大学
https://docker.mirrors.ustc.edu.cn
