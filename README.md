# tcp实现简易的图片传输
## 环境介绍：    
   client ip写死 127.0.0.1 ，C/S端口 6666 
## 使用方法:  
  先运行./server  再运行./client     在server控制台输入`start`开始向所有在线的客户端发送图片（目前固定为一张图片，head.jpg) 发送完成后，断开客户端连接，客户端存储图片名称为年月日时分秒组成的字符串,格式为jpg.  
  退出server,输入命令 `quit`退出.  
## 目前代码宏定义 MAX_CONNECT_NUM为5，最大支持5个客户端连接，超过后无法连接server.  
