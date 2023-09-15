# Node.js彻底卸载(win10)

本文[安装Node.js](https://so.csdn.net/so/search?q=安装Node.js&spm=1001.2101.3001.7020)目录如下:

![image-20230915112352310](Node.js%E5%BD%BB%E5%BA%95%E5%8D%B8%E8%BD%BD(win10).assets/image-20230915112352310.png)

缓存目录: C:\Users\WTG\AppData\Roaming\npm

(https://so.csdn.net/so/search?q=npm&spm=1001.2101.3001.7020)

打开隐藏的项目

![image-20230915112528253](Node.js%E5%BD%BB%E5%BA%95%E5%8D%B8%E8%BD%BD(win10).assets/image-20230915112528253.png)

1. 从卸载程序卸载程序和功能。

2. 重新启动（或者您可能会从任务管理器中杀死所有与节点相关的进程）。

3. 寻找这些文件夹并删除它们（及其内容）（如果还有）。根据您安装的版本，UAC设置和CPU架构，这些可能或可能不存在：

   C:\Program Files (x86)\Nodejs
   C:\Program Files\Nodejs
   C:\Users\{User}\AppData\Roaming\npm（或%appdata%\npm）
   C:\Users\{User}\AppData\Roaming\npm-cache（或%appdata%\npm-cache）

   本人对应安装目录: C:\Users\dell\AppData\Roaming\npm-cache, 

   C:\Users\dell\AppData\Roaming\npm

4. 检查您的%PATH%环境变量以确保没有引用Nodejs或npm存在。

5. 如果仍然没有卸载，请where node在命令提示符下键入，您将看到它所在的位置 - 删除（也可能是父目录）。

6. 重新启动，很好的措施。

------

注意执行上面的清理后，必须重启电脑。





































