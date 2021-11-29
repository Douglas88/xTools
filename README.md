## ❤️ 说明
```
这是一个自己在学习Java GUI开发时实现的产物，目前大部分功能仍待开发，是一个半成品状态，所以它并不是一个开箱即用的趁手工具😊。
```
# xHelper
A tool to quickly collect some information.
###  数据提取（✔️）
数据接口一，无需指定模式：
```
domain=github.com&&port=80
```
数据接口二，与一稍有差别，需要指定提取模式：
```
域名模式：github.com&&port:80
IP模式：185.199.111.0/24
```
###  存活探测（✔️）
批量探测端口存活状态。
![image](https://user-images.githubusercontent.com/45651912/143802394-23fdf22b-1c1b-49b1-b99e-b867d8f050b1.png)

### C段探测（✔️）
指定单条结果跑C段，可以对感兴趣的C段进行快速探测。
![image](https://user-images.githubusercontent.com/45651912/143802662-97a996b2-b7e1-414d-a385-72fab56ef4fd.png)

### 结果导出（✔️）
导出结果为excel。
![image](https://user-images.githubusercontent.com/45651912/143802819-cdf51370-9aea-448f-9d06-316274a22bc2.png)

## TODO
### 多接口提取（🔥）
sumap、hunter、etc。
### 指纹识别（❌）
批量识别高价值web应用。
### 漏洞探测（❌）
调用nuclei完成批量/单个漏洞探测。
