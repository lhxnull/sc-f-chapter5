路由网关(zuul):
Zuul的主要功能是路由转发和过滤器。路由功能是微服务的一部分，比如／api/user转发到到user服务，/api/shop转发到到shop服务。zuul默认和Ribbon结合实现了负载均衡的功能。
zuul有以下功能：

Authentication
Insights
Stress Testing
Canary Testing
Dynamic Routing
Service Migration
Load Shedding
Security
Static Response handling
Active/Active traffic management

``````````````````````````````````````````````````
http://localhost:8769/api-b/hi?name=forezp&token=111
转发到service-feign
http://localhost:8769/api-a/hi?name=lhx&token=1111
转发到service-ribbon


<div align="center"> <img src="C:\Users\Administrator\Desktop\集中配置微服务说明.png" width="450"/> </div><br>

