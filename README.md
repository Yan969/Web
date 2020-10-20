# Web
## 1.http  
超文本传输协议  
#### 1.1 http语义 
HTTP消息主要包括两部分，分别是HTTP语义和HTML实体，了解HTTP语义重点是理解HTTP头部（HTTP Header）。
通过请求/响应消息可以看出，HTTP消息由三部分组成。  
◎请求行或响应行。  
◎HTTP头部。  
◎HTML实体，包括请求实体和响应实体。  
前面两部分是HTTP的语义信息，客户端和服务器使用语义信息进行交谈，最后一部分就是HTML实体，由浏览器进行处理，对用户更有意义。  
#### 1.2 http特点  

## 2.URL  
http:www.example.com:80/index.html  
www.example.com: 服务器名, dns将服务器名转化为ip地址,这样客户端才能找到服务器  
80:端口号(可以省略),表示服务器通过80端口提供http服务  
/index.html:服务器在/根目录下有一个index.html资源
## 3.html  
超文本标记语言
## 4.DNS  
将服务器主机名转换为ip地址  
## 5.客户端  
浏览器, linux的curl工具  

## 6.服务器  
受欢迎的:nginx, apache  
对于服务器开发者来说，提供HTTP服务非常简单，具体如下。  
◎一个域名，这个域名定义了服务器的地址，有了域名，客户端就能够找到服务器。  
◎一台主机，主机绑定域名且用来安装服务器软件，开发者不用自己实现服务器，只要安装服务器软件并启动服务即可，服务绑定80端口，端口的概念本章后续部分会描述。  
◎开发者使用各种语言（比如Python、PHP）编写HTML页面，提供HTTP应用层服务。  
## 7.RFC文档  
http://www.rfc-editor.org/   
http://www.ietf.org/rfc.html  
RFC文档列表：http://www.rfc-editor.org/rfc/  
