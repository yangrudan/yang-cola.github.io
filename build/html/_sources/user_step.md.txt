# 四、使用步骤

## 1. 链接数据源
`添加loki数据源`
![img_5.png](img_5.png)
`填写url`
![img_6.png](img_6.png)
`save&test`测试配置是否成功
![img_7.png](img_7.png)
## 2. 添加Dashboard
Grafana官网提供了很多*Dashboard*进行数据展示：
![img_8.png](img_8.png)
筛选后可以通过`ID或者JSON文件`导入添加到Grafana平台。

***按项目需求定制化Dashboard***

## 3. Glog面板
promtail搜集的日志目录：
![img_10.png](img_10.png)
glog的行数25*6 = 150 行
![img_9.png](img_9.png)
`搜索功能`（查找到”85th")
![img_11.png](img_11.png)
## 4. python在Web中调用
分享Dashboards的地址
![img_12.png](img_12.png)
在python的html加入地址
![img_13.png](img_13.png)
在自己项目的网页监控日志：
![img_14.png](img_14.png)
