# HydrogenMinecraftECLauncher
## 前言
HydrogenMinecraftECLauncher是一个由易语言写的启动模块,我叫他HCL

写这个模块主要的原因是有个大聪明,把mc的启动参数直接复制到e语的”运行()”里,然后说他做了个启动器…

当时血压就上来了,傻傻比比的立了个flag:"我要是什么时候有空,我直接给你写个真正意义上的启动器."

结果我就掉这坑里了,硬是写了两天才把启动和补全文件写完…搞掉我脑子都是糊的,而且当时没有写注释和规范变量名的意识,后面代码量一上来我就弃坑了.

但我当时说了开源,又不能说话不算数啊,所以现在又回来了.

现在还在写注释和规范变量名
## 功能
### 已完成
- [x] 补全资源
- [x] 启动原版游戏
- [x] 修改窗口标题
### 未完成
- [ ] forge版启动
- [ ] 自动安装forge
- [ ] java自动下载
## 使用说明
注:好久以前的东西了,不保证能用.forge没做完,opt也没做完,微软登录没账号,没做.

### 补全文件
补全文件会有点慢,具体原因不清楚.
~~~
.版本 2

HCl_v1_补全文件 (“1.17.1-forge-37.0.1”, 2, 128)
~~~

### 启动游戏
~~~
.版本 2

HCLAPI.V2.设置MC路径 (“.minecraft”)
HCLAPI.V2.启动游戏 (“E:\jdk1.8.0_261\bin\javaw.exe”, “1.12.2”, 1024, “hsn”)
~~~

