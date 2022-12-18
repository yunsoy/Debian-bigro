---
title: "Blog"
date: 2022-12-14T16:49:01+08:00
draft: false 
---

# Linux BigProject

## Complete the Steps

### (1)
下载git，生成密钥对连接github    
sudo apt install git  
ssh-keygen -t rsa -C "email"  
![图1](/images/图片1.png)  
![图2](/images/图片2.png)  
![图3](/images/图片3.png)  
查看并使用生成的公钥连接远程仓库    

### (2)
用soket创建编写sever.cpp与client.cpp并进行编译    
![图11](/images/图片11.png)
![图12](/images/图片12.png)   
![图13](/images/图片13.png)
![图14](/images/图片14.png)
![图15](/images/图片15.png)   
![图16](/images/图片16.png)    
![图4](/images/图片4.png)   
![图5](/images/图片5.png)

### (3)
下载hugo    
sudo apt install hugo
![图6](/images/图片6.png)

创建站点mylog    
hugo new site mylog
![图7](/images/图片7.png)
  

在themes中下载主题,并按照官方文档进行配置    
git clone https://    
![图8](/images/图片8.png)

试运行    
hugo server -t angels-ladder（主题名)  

正式运行    
hugo sever --bind=0.0.0.0 --baseUrl=网址
![图9](/images/图片9.png)
![图10](/images/图片10.png)
