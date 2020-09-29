# 沙箱环境使用说明

## 环境介绍
该环境是一套独立的运行容器。只需要通过浏览器即可与容器交互。
本环境提供命令行、文件浏览器两种交互方式，你可以选择你习惯的使用方式。
通过这些工具，您可以在查看、修改、编译、运行您的 java 代码。

代码工程首次下载以后，请点击目录树的刷新按钮（下图中绿色箭头所示）刷新目录树，以便于通过图形界面浏览和修改代码：
![image](https://img.alicdn.com/tfs/TB14b9Ei5pE_u4jSZKbXXbCUVXa-746-398.png)


## 代码编译
如果您使用 maven 构建，请使用如下命令打包：
```bash
mvn clean package
```

## 运行程序
进入 maven 打包输出目录
```bash
cd target
```

使用 java 命令启动程序
```bash
java -jar demo-0.0.1-SNAPSHOT.jar
```