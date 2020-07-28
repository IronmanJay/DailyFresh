# 一、天天生鲜项目简介  
&nbsp;&nbsp;上面是整个源码包，里面有所需要的所有素材，照片，js，css等，代码我均已注释清晰。整个项目基于django框架的website，是一个电商项目，功能齐全，用户注册登录缓存放在redis，用户信息商品信息等放于mysql，使用搜索引擎框架实现搜索功能，增加其他功能，如分页，乐观锁，分布式存储等优化功能，实现接口对接付款评价等功能，大家可以使用uwsgi作为web服务器使用nginx部署。温馨提示，下载源码包大体代码不变，但是在settings里面需要修改为您的数据库地址。  
# 二、项目构成  
1. whoosh_index：搜索引擎框架 
2. utils：工具类  
3. templates：html文件  
4. static：静态资源文件 
5. db：数据库配置  
6. dailyfresh：项目整体配置  
7. apps：具体功能实现  
&nbsp;&nbsp;① user：用户功能模块  
&nbsp;&nbsp;② order：购物车功能模块  
&nbsp;&nbsp;③ goods：商品功能模块  
&nbsp;&nbsp;④ cart：购物车功能模块  
