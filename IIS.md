WCF 404.3 MIME 映射错误
=========================
　今天想把WCF服务用IIS启动起来进行调试。捣鼓半天老报错误：<br>
  >HTTP 错误 404.3 - Not Found <br>
  由于扩展配置问题而无法提供您请求的页面。如果该页面是脚本，请添加处理程序。如果应下载文件，请添加 MIME 映射。
  
  静下心来仔细观察错误原因，可能是.svc文件类型没有在MIME中进行配置，但是MIME又怎么配置呢？继续百度，幸好发现此篇文章：
 [WCF 404.3 MIME 映射错误](http://jiajietieren.blog.163.com/blog/static/6018694220123185505272/)。需要打开Windows服务才行。
 