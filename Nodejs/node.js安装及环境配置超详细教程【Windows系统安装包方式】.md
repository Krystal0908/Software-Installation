# node.js安装及环境配置超详细教程

## **Step1：下载安装包**

软件下载地址：

```powershell
https://nodejs.org/zh-cn/download
```

根据自己电脑系统及位数选择，我的电脑是Windows系统、64位、想下载稳定版的.msi（LTS为长期稳定版）这里选择`windows64位.msi`格式安装包。

`.msi`和`.zip`格式区别：

- `.msi`是Windows installer开发出来的程序安装文件，它可以让你安装，修改，卸载你所安装的程序。说白了.msi就是Windows installer的数据包，把所有和安装文件相关的内容封装在一个包里。*此外：它还包含有关安装过程自己的信息。例如：安装序列、目标文件夹路径、安装选项和控制安装过程的属性。*
- `.zip`是一个压缩包，解压之后即可，不需要安装

下载方式1：[官网下载页进行下载](https://link.zhihu.com/?target=https%3A//nodejs.org/zh-cn/download/)

![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-f5f138a318ba076c4807946872b22ae3_720w.webp)

下载方式2：[官网首页直接下载](https://link.zhihu.com/?target=https%3A//nodejs.org/zh-cn/)

![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-dd2c8cc86ff70b3d1c6b2a46c3e38062_720w.webp)



## **Step2：安装程序**

1. 下载完成后，双击安装包，开始安装，使用默认配置安装一直点`next`即可，安装路径默认在`C:\Program Files`下，也可以自定义修改

   ![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-4a9aef2e14ce82167a21be1a2f87c3c6_720w.webp)

   ![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-11e968c664c00553a2b29d5e1d473976_720w.webp)

   

2. 安装路径默认在C:\Program Files下面，也能够自定义修改，而后点击next（我这里设置我的安装目录为`E:\KF\node.js\` 根据自己的需要进行更改。）

   ![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-47b06d004d5a70b761bb14bc5a76fd23_720w.webp)

   

3. 下图根据本身的需要进行，我选择了默认`Node.js runtime`，而后`Next`

   - `Node.js runtime` ：表示运行环境

   - `npm package manager`：表示npm包管理器

   - `online documentation shortcuts` ：在线文档快捷方式

   - `Add to PATH`：添加到环境变量

     ![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-5c0836086826ad88c48b608ebb9cd792_720w.webp)

   

4. 以下图框中所示，我没有选中，而是直接next

   ![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-a1685870d2a2d6fa943dd6b820f16d16_720w.webp)

5. 点击Install，进行安装

   ![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-a2042b63a125897f50d4b1ad86cd72a9_720w.webp)

6. 点击finish，完成安装

   ![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-b417afc07d2fbfe8a3958ae7a660e583_720w.webp)

7. 安装完成后，.msi格式的安装包已经将node启动程序添加到系统环境变量path中,咱们能够查看系统变量进行验证：在【个人电脑】右键→【属性】→【高级系统设置】

   ![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-633b35fd90ec45a050c5d365547f731f_720w.webp)

8. 点击【高级】→【环境变量】

   ![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-6f40e56125a9e99e722e5eb3cad3afcf_720w.webp)

9. 在系统变量中查看【path】，点击【编辑】

   ![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-75f8d6f59a9ffbb17397070ba6552fef_720w.webp)

10. 会发现.msi格式的安装包已经将node启动程序添加到系统环境变量path中

    ![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-bdcb15d7a83c050d7eec569f159adb74_720w.webp)



## **Step3：查看**

1. 既然已经将node程序添加到全局系统变量中，把咱们能够直接在CMD窗口中任意位置执行node，打开CMD窗口，执行命令`node -v`查看node版本

   【注意：此时是打开CMD窗口，并非在C:\Program Files\nodejs目录下执行node.exe】

   ![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-77f00ac9d9d97834a2553842ce4320c6_720w.webp)

2. 最新版的node在安装时同时也安装了npm,执行`npm -v`查看npm版本

   ![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-0d645b1e29e4d3ce2013f41c2010db71_720w.webp)

3.  默认状况下，咱们在执行npm install -g XXXX时，下载了一个全局包，这个包的默认存放路径C:\Users\Administrator\AppData\Roaming\npm\node_modules下，能够经过CMD指令`npm root -g`查看

   ![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-145cacd1023094f3c742b02dc9e20736_720w.webp)

4. 一部分经常使用的命令，以下：

   - npm -v：查看npm安装的版本。
   - npm init：会引导你建立一个package.json文件，包括名称、版本、作者等信息。
   - npm list：查看当前目录下已安装的node包。
   - npm ls：查看当前目录下已安装的node包。
   - npm install moduleNames：安装Node模块到本地目录node_modules下。
   - npm install < name > -g：将包安装到全局环境中。
   - npm install < name > --save：安装的同时，将信息写入package.json中，项目路径中若是有package.json文件时，直接使用npm install方法就能够根据dependencies配置安装全部的依赖包，这样代码提交到git时，就不用提交node_modules这个文件夹了。
   - npm install < name> --save-dev：安装的同时，将信息写入package.json中项目路径中若是有package.json文件时，直接使用npm install方法就能够根据devDependencies配置安装全部的依赖包，这样代码提交到git时，就不用提交node_modules这个文件夹了。
   - npm uninstall moudleName：卸载node模块。

   

## **Step4：环境配置**

1. 打开安装的目录（默认安装情况下在D:\ProgramFiles\developer_tools\Nodejs18）

2. 在安装目录下新建两个文件夹【node_global】和【node_cache】

   ![image-20230915092826462](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/image-20230915092826462.png)

3. 再次打开cmd命令窗口，输入npm config set prefix “你的路径\node_global”（`“你的路径”默认安装的状况下为 D:\ProgramFiles\developer_tools\Nodejs18`）

   ```sh
   npm config set prefix "E:\KF\nodejs\node_global"
   ```

   

4. npm config set cache “你的路径\node_cache” 可直接复制刚刚新建的空文件夹目录

   ```sh
   npm config set cache "E:\KF\nodejs\node_cache"
   ```

   执行的时候建议使用管理员权限打开CMD，否则有可能会提示权限不够报错

   ![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-e3c2c46ee559de286a62a456452cde24_720w.webp)

5. 设置环境变量，打开【系统属性】-【高级】-【环境变量】，在`系统变量`中新建

   变量名：`NODE_PATH`

   变量值：`D:\ProgramFiles\developer_tools\Nodejs18\node_global\node_modules`

   （ 用来告诉系统， 下载的模块或者包都在这里了）

   ![image-20230915092949740](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/image-20230915092949740.png)

   ![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-9f482a1d371cdab2c14bef40bc3c984b_720w.webp)

6. 编辑`用户变量（环境变量）`的 path，将默认的 C 盘下 `APPData\Roaming\npm` 修改成 `D:\ProgramFiles\developer_tools\Nodejs18\node_global`，点击确定

   ![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-694655cfc6dcd5fe360fb45a92ee438e_720w.webp)

   最后别忘了在`Path`里面添加`NODE_PATH`

   ![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-88c0dd8bd129b0d7f8a5b00afaf40848_720w.webp)

7. 测试，配置完成后，安装个module测试下，咱们就安装最经常使用的express模块，打开cmd窗口，输入以下命令进行模块的全局安装：

   ```sh
   npm install express -g   // -g是全局安装的意思
   ```

   ![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-1b0ec87759a0d6e04ede15cb7b6f8ce1_720w.webp)

## **最后补充：**

经过npm安装模块时都是去国外的镜像下载的，可是有的时候因为网络等缘由致使安装模块失败，好在阿里有团队维护国内镜像 [淘宝 NPM 镜像](https://link.zhihu.com/?target=https%3A//npmmirror.com/) ，上面有使用说明，你们可自行查看

**添加国内镜像源：**如果没有梯子的话，可以使用阿里的国内镜像进行加速。

```sh
npm config set registry https://registry.npm.taobao.org
```

![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-d0760ebb861f2d232b6b673afda56fbe_720w.webp)

![img](node.js%E5%AE%89%E8%A3%85%E5%8F%8A%E7%8E%AF%E5%A2%83%E9%85%8D%E7%BD%AE%E8%B6%85%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B%E3%80%90Windows%E7%B3%BB%E7%BB%9F%E5%AE%89%E8%A3%85%E5%8C%85%E6%96%B9%E5%BC%8F%E3%80%91.assets/v2-06106a40c37588e516d8d22723a588d7_720w.webp)



使用定制的 cnpm (gzip 压缩支持) 命令行工具代替默认的 npm:

```bash
npm install -g cnpm --registry=https://registry.npmmirror.com
```





































































