# docker_kali


docker build -t  kali .

docker run -d --name kali -p 80:80 -p 2222:22 -p 3000:3000 -p 4444:4444 -p 5555:5555  -p 8080:8080 kali /bin/bash /run.sh

docker exec -it kali /bin/bash


root密码：demon


开机自启apcahe2  ssh服务  


内置自动化安装配置sqlmap/ssh/apache/,可在dockerfile 自定义添加更改自己所需要的软件
