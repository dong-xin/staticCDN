# staticCDN(静态资源CDN)  
>1.创建仓库(create repository)  
2.git拉取到本地(git pull)  
3.将js、image、MP3、MP4等文件加入到仓库中(git add)  
4.git推送仓库(git commit/push)  
5.访问：  
- https://cdn.jsdelivr.net/gh/username/repository@branch/directory path/filename  
jsdelivr提供免费CDN加速服务，官网：https://www.jsdelivr.com/，支持npm、github、wordPress文件解析  
https://cdn.jsdelivr.net/gh/：为固定语法  
username：github上用户名  
repository：github上仓库名  
branch：github上分支名  
directory path：github上完整目录路径  
filename：github上目录路径下的文件名  
- https://cdn.jsdelivr.net/gh/username/repository@release version/directory path/filename  
release version：github上发布的版本号  
发布应用：github仓库-->发布:创建发版-->输入版本号-->输入发包标题-->输入发版描述
-->勾选:是否预发布版-->确定发布  
- https://cdn.jsdelivr.net/gh/username/repository@release version/directory path/  
不加文件名，则访问整个目录文件

>6.栗子：  
https://cdn.jsdelivr.net/gh/dong-xin/staticCDN@v0.1/file/image/2020/08/IMG_1404-d213eb39453e49bdb1fc614a7e20d4d4.jpeg  
https://cdn.jsdelivr.net/gh/dong-xin/staticCDN@master/file/image/2020/08/IMG_1404-d213eb39453e49bdb1fc614a7e20d4d4.jpeg  
https://cdn.jsdelivr.net/gh/dong-xin/staticCDN@master/file/  
  
 
