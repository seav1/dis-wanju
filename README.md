# 玩具鸡通用脚本


第一：包含三种平台脚本，脚本功能一样，都是调用start.sh脚本启动xray

第二：仓库中提供一个F大的脚本start.sh，仅供参考

第三：下面以wyldhost.de和cortexnodes.com为例简单展示java使用方法，其他类似，

1、修改玩具容器的启动文件为server.jar

![image](https://github.com/seav1/dis-wanju/blob/main/png/1.PNG)

2、上传文件本仓库中的server.jar和start.sh,修改start.sh中的变量

![image](https://github.com/seav1/dis-wanju/blob/main/png/2.PNG)


3、修改server.jar和start.sh权限为777，然后运行

![image](https://github.com/seav1/dis-wanju/blob/main/png/3.PNG)

4、某些平台为ARM如cortexnodes.com，需要将脚本换成arm的脚本，其他一样
