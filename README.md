# tomcatfix
Scope: Connection refused on port 8080

Steps to troubleshoot
netstat -lntp 
#if port 8080 is not listed among the listening ports, please use the link below and change accordingly.
Change 8005 to 8006 from this line 
<Server port="8006"shutdown="SHUTDOWN">
https://stackoverflow.com/questions/21021136/tomcat-starts-but-home-page-cannot-open-with-url-http-localhost8080

NB: Make sure you start tomcat AGAIN by using the following: starttomcat![image](https://user-images.githubusercontent.com/111421200/193488943-8175f317-7210-4e1c-802a-d59acfce9984.png)
