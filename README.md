### assets代理工具

####使用方法

#####clone代码库 

#####1.配置host  

```
# 本地代理(g.tbcdn.cn)
127.0.0.1 g.tbcdn.cn g.assets.daily.taobao.net
```

#####2.进入目录，执行proxy-c.js
```
cd proxy4gitlab
node proxy-c.js //注：mac下需要用 sudo node proxy-c.js才能打开80端口
```

#####3.打开浏览器 输入http://g.tbcdn.cn

#####4.配置group project

eg: http://g.tbcdn.cn/tb/ticket/1.2.0/convenience/css/index-min.css

group:tb   

project:ticket  

#####5.配置完毕 重启服务器


