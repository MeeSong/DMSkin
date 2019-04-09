# DMSkin

## 目前项目还在开发中，仅供参考

#### 介绍
#### 这是一个全新的项目，快速开发WPF客户端的框架。
#### 内容：MVVM 框架模块 + DesignLibrary 控件样式库
#### 开发PC客户端 一套搞定


<img src="https://raw.githubusercontent.com/944095635/DMSkin/master/Docs/Image/Demo.png" width="615" height="395" align="center">

## 1.开发&编译&环境&问题

<img src="https://raw.githubusercontent.com/944095635/DMSkin/master/Docs/Image/VS.png" width="310" height="101" align="center">

````xml
开发环境：Windows 10  +  Visual Studio 2019 Professional  +  .Net Framework 4.5

项目基于Visual Studio 2019 Professional .Net Framework 4.5，源码包括一些C#新语法。

如果你在旧版本Visual Studio版本上编译不通过的话，请自行修改中源码不兼容的部分。
````
````xml
支持环境：Windows 7/10 +  .Net Framework 4.5
````
````xml
1.目前绝对放弃Windows XP
2.WPF多数是企业软件,如果要适配windows 7,单独装.Net Framework 4.5的库
3.UI库的初衷就是为了制作更精美的界面,精美的效果在旧系统中并不能正常的显示,
  为了适配旧版本的系统而放弃语言新特性,得不偿失。

目前Windows 10 占有率已经超过Windows 7
````
````xml
注意：系统阴影(如果用户关闭了窗口阴影,界面边界无法分辨，可以考虑使用Border增加窗口边框)
我的电脑->此电脑->高级系统设置->性能->设置->√ 在窗口下显示阴影
````
````xml
Windows XP 请自行测试,
旧版本已经被我转移到[DMSkin-for-WPF](https://github.com/944095635/DMSkin-for-WPF)(备份学习之用)
````
## 2.项目模块&使用说明

| 项目               |   描述                         | 最新版本            | Nuget |
| :----:            |   :----:                       |   :----:       |:----:  | 
| DMSkin            | DMSkin 基础控件 .Net Framework 4.5+       | 3.0.0.1000     |        |
| DMSkin.Core       | MVVM,Broadcast,DelegateCommand,ViewModelBase | 3.0.0.1000     |        |

| DesignLibrary样式库| 依赖于DMSkin.dll                | 最新版本      | Nuget |
| :----:            |   :----:                       |   :----:       |:----:  | 
| DMSkin.AntDesign  | Ant Design https://ant.design  | 1.0.0.1000     |        |
| DMSkin.AduDesign  | Adu为DMSkin设计的样式库          | 1.0.0.1000     |        |

DesignLibrary样式库都依赖于DMSkin.dll。

DMSkin.dll 可以独立存在。

DMSkin.Core.dll 可以独立存在。


#### 2.1 DMSkin中的Core模块(DMSkin.Core.dll)
> Execute(跨线程UI调度器) [[使用文档]](https://github.com/944095635/DMSkin/wiki/Execute%E8%B7%A8%E7%BA%BF%E7%A8%8BUI%E8%B0%83%E5%BA%A6%E5%99%A8)

> Broadcast(广播器) [[使用文档]](https://github.com/944095635/DMSkin/wiki/Broadcast%E5%B9%BF%E6%92%AD%E5%99%A8)

> TaskManager(Task管理器)

> DelegateCommand(ICommand实现)

> ViewModelBase(ViewModel基类)

#### 2.2 DMSkin模块(DMSkin.dll)
> DMSkinWindow[[使用文档]](https://github.com/944095635/DMSkin/wiki/DMSkinWindow%E7%AA%97%E5%8F%A3)

> SystemButton(系统按钮)

> Icon(附加属性类)


## 3.下载&引用
> 3.1 可以直接通过   `https://github.com/944095635/DMSkin.git`

克隆代码到本地，通过引用项目的方式导入DMSkin到你的解决方案中

> 3.2 你可以通过Nuget 搜索DMSkin安装到自己的项目中

## 4.代码段
项目中一般会使用到Visual Studio的智能提示(双tab代码段),

我在项目中提供了3个代码段（在当前项目的Docs文件夹中可以找到）。

VS->工具->代码片段管理器->语言（Csharp）->Visual C#

我的VS安装在C盘路径是:
````xml
C:\Program Files (x86)\Microsoft Visual Studio\2019\Professional\VC#\Snippets\2052\Visual C#
````

| Dos文件夹                | 描述   |使用率   |
| :----:              | :---:          | :---:          |
| propfull  |  刷新属性       |⭐⭐⭐|
| propob  |  刷新集合属性       |⭐⭐⭐|
| command   | 命令        |⭐⭐|
| propdp    | 依赖属性    |⭐|
| propa    | 附加属性    |⭐|


## 5.库介绍

### 5.1 DMSkin 


### 5.2 DMSkin.Core 


### 5.3 DMSkin.AntDesign 
AntDesign Design https://ant.design
