[TOC]
## 内容介绍

今天给大家分享一款sketch插件，利用该插件可以实现代码自动生成，并且包含多端。例如web端，微信小程序端等。
## imgcook介绍

imgcook **专注以 Sketch、PSD、静态图片等形式的视觉稿作为输入**，通过智能化技术**一键生成可维护的前端代码，包含视图代码、数据字段绑定、组件代码、部分业务逻辑代码**等。目前此产品是阿里巴巴前端委员会智能化小组的服务化的内外落地产品。
imgcook 的主要功能是视觉稿一键还原和基于还原后的可视化编辑，Sketch/Photoshop 设计稿的还原从安装插件开始，在设计稿中通过插件导出视觉稿的 JSON 描述信息粘贴到 imgcook 可视化编辑器，在编辑器中可以进行视图编辑、逻辑编辑等，生成代码后可将代码导出到本地或您的工程文件。主流程如下箭头所示

![](https://oscimg.oschina.net/oscnet/up-100df63ec28e61f3b96ce90802ee3e5c28f.png)

### 使用场景

imgcook 目前支持各种场景的页面或模块的高度还原，您可以根据以下场景分类选择是否使用 imgcook。
1. 移动端细粒度模块开发场景 - 特别推荐
2. 移动端活动页 - 特别推荐
3. 移动端全页面开发 - 推荐
4. PC 端 toC 应用 - 推荐
5. PC 端 toB 应用
6. PC 端富交互应用 - 不推荐
7. 游戏场景 - 不推荐
## 使用流程

1. 设计师根据 设计稿规范 调整设计稿，确保图层组织以及切图相关的质量交付，完成后交于前端。
2. 前端根据设计师调整后的设计稿，可选中模块或页面进行导出（使用插件或者文件上传服务）。
3. 前端根据设计稿导出还原后的结果在编辑器中进行微调使用。
## 软件安装

1.sketch安装。这里就不演示如何安装。如果需要破解版的，可以关注公众号(卡二条的技术圈)回复，"sketch",即可免费获取最新破解包。

2.imcook安装。

2.1我们先打开官网地址。[官网地址](https://imgcook.taobao.org/) 将插件下载到本地，点击该插件即可自动安装到sketch插件中。

![](https://oscimg.oschina.net/oscnet/up-c1946b3758b58294d5a9c564874bfbe39d5.png)

3.检测插件是否安装成功。打开sketch，点击插件管理菜单，如果现实imgcook则表示安装成功。同时我们也可以看到sketch的工作界面右侧多了几个菜单选项。
![](https://oscimg.oschina.net/oscnet/up-215f6cee0b169a8f49f4ae7259dcd19c9a9.png)

## 如何使用

1.我们事先找一个sketch文件，我这里去网上找的一个sketch元件。导入到sketch中。我们选中元件，点击右侧的导出按钮即可。

![](https://oscimg.oschina.net/oscnet/up-c376e9ec39f9d3103a3a79f5e395741ea2d.png)

2.复制导出的链接。会自动跳转到imgcokke的官网中去。

![](https://oscimg.oschina.net/oscnet/up-16bfe0ef69b0f360e3d20ad6dfb9112385b.png)

3.点击复制按钮，会默认跳转到该界面。我们直接按住ctrl+v,粘贴即可。

![](https://oscimg.oschina.net/oscnet/up-396e4606431df52307eeb252eef8e0de4ef.png)

4.此时点击右上角的代码按钮，即可选择不同端口的代码。

![](https://oscimg.oschina.net/oscnet/up-b68f2f0de5fcf894da4ab35ccccf9b4f312.png)

5.默认的是web端的代码，我们可以看到几个选型卡，这几个选项卡就是我们常见的html,css，js等文件。

![](https://oscimg.oschina.net/oscnet/up-e92b54e94a5e426babc9823e1543f160b75.png)

6.根据需要，自动生成多端代码。

![](https://oscimg.oschina.net/oscnet/up-379eae7d42c47efe2f644518a687cdace3e.png)

7.自动调整元素。如果需要调整sketch元件的设计，我们可以点击编辑模式，根据不同的选项，进行配置。

![](https://oscimg.oschina.net/oscnet/up-6be5ceb2b82619fcad0fdd90b9524b1b795.png)

8.最后我们根据我们常见的操作，创建html，css和js文件，imgcook创建好的代码导入进去就可以啦。这里就不演示了。