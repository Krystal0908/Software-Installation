# **yarn 不是内部或外部命令,也不是可运行的程序（亲测可用）**

## 这个时候报 yarn 不是内部或外部命令 相信你的npm已经安装好了

1. 方法一（网上大多数是这个）：

   ```sh
   npm install -g yarn
   ```

   

2. 方法二（我的是这个）：配置环境变量（你的yarn地址直接复制上去就好了）

```powershell
D:\ProgramFiles\developer_tools\Nodejs18\node_global\node_modules\yarn\bin
```

![image-20230915172806931](yarn%20%E4%B8%8D%E6%98%AF%E5%86%85%E9%83%A8%E6%88%96%E5%A4%96%E9%83%A8%E5%91%BD%E4%BB%A4,%E4%B9%9F%E4%B8%8D%E6%98%AF%E5%8F%AF%E8%BF%90%E8%A1%8C%E7%9A%84%E7%A8%8B%E5%BA%8F%EF%BC%88%E4%BA%B2%E6%B5%8B%E5%8F%AF%E7%94%A8%EF%BC%89.assets/image-20230915172806931.png)

![image-20230915173017305](yarn%20%E4%B8%8D%E6%98%AF%E5%86%85%E9%83%A8%E6%88%96%E5%A4%96%E9%83%A8%E5%91%BD%E4%BB%A4,%E4%B9%9F%E4%B8%8D%E6%98%AF%E5%8F%AF%E8%BF%90%E8%A1%8C%E7%9A%84%E7%A8%8B%E5%BA%8F%EF%BC%88%E4%BA%B2%E6%B5%8B%E5%8F%AF%E7%94%A8%EF%BC%89.assets/image-20230915173017305.png)

## 双击yarn.cmd和yarnpkg.cmd

![image-20230916005433375](D:/Study/Git-Space/Git-Download/Software-Installation/Nodejs/yarn%20%E4%B8%8D%E6%98%AF%E5%86%85%E9%83%A8%E6%88%96%E5%A4%96%E9%83%A8%E5%91%BD%E4%BB%A4,%E4%B9%9F%E4%B8%8D%E6%98%AF%E5%8F%AF%E8%BF%90%E8%A1%8C%E7%9A%84%E7%A8%8B%E5%BA%8F%EF%BC%88%E4%BA%B2%E6%B5%8B%E5%8F%AF%E7%94%A8%EF%BC%89.assets/image-20230916005433375.png)

- 测试

  ```powershell
  yarn -v
  ```

  ![image-20230916010009883](D:/Study/Git-Space/Git-Download/Software-Installation/Nodejs/yarn%20%E4%B8%8D%E6%98%AF%E5%86%85%E9%83%A8%E6%88%96%E5%A4%96%E9%83%A8%E5%91%BD%E4%BB%A4,%E4%B9%9F%E4%B8%8D%E6%98%AF%E5%8F%AF%E8%BF%90%E8%A1%8C%E7%9A%84%E7%A8%8B%E5%BA%8F%EF%BC%88%E4%BA%B2%E6%B5%8B%E5%8F%AF%E7%94%A8%EF%BC%89.assets/image-20230916010009883.png)



# yarn create @umijs/umi-app 报错：文件名、目录名或卷标语法不正确

解决地址：

https://github.com/yaoningvital/blog/issues/207#issue-585631854

> 最后！最后！最后！
>
> 记得重新打开dos窗口（不管修改什么程序的环境变量，都必须重新打开dos窗口，才会生效）