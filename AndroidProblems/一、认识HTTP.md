#### 一、HTTP是什么？

用于传输超文本的协议。以前是HTML，现在也包括Web API的数据

HTTP工作模型：客户端按需求组装HTTP报文，发送给服务器，服务器处理后得到响应报文，发回给客户端，客户端处理响应报文

#### 二、URL组成：协议类型、服务器地址、路径（path）

#### 三、报文格式：状态行、Headers、body



#### 四、Header

* 作用：http 消息的元数据（meta data）

* Host：服务器主机地址

* Content-Type/Content-Length: Body的类型/长度

* Location:重定向的目标 URL

* User-Agent： 用户代理

* Range/Accept-Range:指定Body的内容范围

* Cookie/Set-Cookie:发送Cookie/设置Cookie

* Authorization: 授权信息

##### 部分Header：

* Accept:客户端能接受的数据列星。 如：text/html

* Accept-Charset：客户端接受的字符集。如 utf-8

* Accept-Encoding： 客户端接受的压缩编码类型。如 gzip

* Content-Encoding: 压缩类型。如 gzip

#### 五、 什么是REST？

正确使用HTTP（按照http软件架构规范使用http）

