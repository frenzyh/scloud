# scloud
Cloud disk based on  cryptography   
background:  
Linux Python 2.7.9 MySQL > 5  
pip install MySQLdb  
***********************************************
client:

python client_new.py -h

Usage: client_new.py [options]

Options:
  -h, --help            show this help message and exit
  -s SERER_ADDRESS, --server=SERER_ADDRESS
                        the server's ip address
  -p PORT_NUMBER, --port=PORT_NUMBER
                        the port number of server

-----------------------------------------------

[*] Welcome to Scloud_client  
[*] Please login or register first  
[*] The options you can use are('back' can be used to swicth option):  
[*] help, exit, register, login, upload, download, share  
Scloud>   

choose the option to use :)  

**********************************************
server:  
python server_new.py   
note: authorise manually !!!  

#基于密码技术的安全传输云盘  
说明：  
这是一个基于密码学的安全云盘。  
模拟云盘认证部分参考了新浪微盘认证过程及代码。  
在Windows 8.1 与 liunx 上测试通过  

使用说明

适用于Python 2.7.9 MySQL大于5 环境  
首先简易安装MySQLdb  
先进行网盘认证（必须进行手动授权），运行服务，最后运行客户端  
***********************************************
运行client:  
python client_new.py -h  
Usage: client_new.py [options]  

Options:  
  -h, --help            show this help message and exit  
  -s SERER_ADDRESS, --server=SERER_ADDRESS  
                        the server's ip address  
  -p PORT_NUMBER, --port=PORT_NUMBER  
                        the port number of server  

-----------------------------------------------
进入客户端界面  
[*] Welcome to Scloud_client  
[*] Please login or register first  
[*] The options you can use are('back' can be used to swicth option):  
[*] help, exit, register, login, upload, download, share  
Scloud>   
choose the option to use :)  
**********************************************
运行server:  
python server_new.py   

#已知问题：
1、手动认证
2、功能不够全面，私密分享、分享等
3、数据库需要自我搭建
4、对于Windows用户不够友好
