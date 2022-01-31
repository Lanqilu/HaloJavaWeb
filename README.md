## Java Web

web.xml 配置

```xml
<?xml version="1.0" encoding="UTF-8"?>

<web-app xmlns="http://xmlns.jcp.org/xml/ns/javaee"
         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://xmlns.jcp.org/xml/ns/javaee
                      http://xmlns.jcp.org/xml/ns/javaee/web-app_4_0.xsd"
         version="4.0"
         metadata-complete="true">
</web-app>

```

war 模式这种可以称之为是发布模式，就是先将 Web 工程打成 war 包，然后再将其上传到服务器进行发布

war exploded 模式是将 Web 工程以当前文件夹的位置关系上传到服务器，即直接把文件夹、jsp 页面 、classes 等等移到 Tomcat 部署文件夹里面，进行加载部署。因此这种方式支持热部署，一般在开发的时候也是用这种方式。