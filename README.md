# guidance-for-beginners
APICloud 新手开发指南。the APICloud guidance for beginners. 


> 移动端开发大致分为以下四个级别，分别介绍了每个级别需要了解和掌握的内容：

**`初级`**  熟悉HTML/CSS/JS前端技术，了解 APICloud 开发，能使用开发工具运行和预览模板项目，能使用开发控制台云编译生成正式版应用。

**`中级`**  熟悉移动开发概念和术语，熟悉 APICloud 开发流程，掌握引擎和模块 API 的基本使用以及帮助文档的阅读，能进行正式项目的页面交互开发。

**`高级`**  精通前端技术和 APICloud 多端开发，具备熟练使用和封装多端组件能力，能够独立完成商业项目开发。

**`专家`**  熟悉 APICloud 技术和产品体系，精通前后端开发流程，对移动应用体验和性能有深入理解，具备项目工程化和提供解决方案能力。

# 移动端开发知识体系



##  1. 基础知识

> 在开始学习移动端开发之前，需要具备一定的开发知识，以便于更好的学习和理解移动端开发相关内容。
>
> 在这一部分里面，主要分为【1.1 前置基础】和【1.2 平台基础】。

### 1. 1 前置基础

> 前置基础是学习移动端开发的必要门槛，要求开发者具备以下能力或者知识储备。
>
> 由于跨端移动端开发主要还是使用前端开发技术，辅以部分平台特征代码来实现的，所以三门前端基础语言【1.1.1 HTML/CSS/JS】是必要的。
>
> 在条件允许的情况下，通过【1.1.2 多端跨平台技术】了解时下主流的多端跨平台开发的技术选型和原理，有助于更好的理解移动端开发和开发出优质的应用。

#### 1.1.1 HTML / CSS / JS 【初级】

#### 1.1.2 多端跨平台技术【中级】

- 《参考链接》：（本部分内容属于通用性技术指南，可以从互联网获得相关知识。）

### 1.2.  平台基础

> 在学习完成前置知识以后，可以进一步向移动端开发平台相关知识迈进。在学习的开始，需要了解 APICloud 的发展历史，有助于理解 APICloud 架构和技术原理。
>
> 【历程】APICloud 上线于 2014 年，时值 APP 开发火热之时。为了解决原生开发 APP 难度大、效率低和专业人员短缺的情况下，APP 开发市场需求缺口较大的情况下，APICloud 推出基于 WebView 的深度跨端开发引擎 ，赋能普通的前端开发者使用现有技术，快速转化为移动端 APP 开发者。
>
> 【生态能力】在发展过程中，与操作系统版本紧密联系，保持引擎不停地迭代升级。开放了模块开发规范，建立了良好的模块生态市场。包括官方、第三方服务商和个人开发者贡献了一千多个优质的原生模块，便于前端开发者使用。
>
> 【云平台基础】中会初步介绍控制台的功能和使用方法，以便日后知识点涉及到详细操作时，更加容易找到相关位置。
>
> 【快速上手】则整理了一些新手初体验的文档、指南和视频教程的链接。
>
> 【AVM 多端演进】在 2020 年，APICloud 平台为了提升应用性能和增加构建多端应用的能力，特别地推出了 AVM 多端开发引擎，来作为 APICloud 3 的版本。AVM 版本可以使用一套代码同时适配 Android / iOS、微信小程序和 H5 应用。此时，APICloud 开启双引擎渲染模式：1. WebView 模式，可以使用 HTML 来开发界面和应用；2.  AVM 多端引擎模式，使用 STML 语言来开发原生渲染的界面。
>
> 【融合】在 2021 年，APICloud 融入用友体系下，成为用友移动端开发的选择。目前友空间 APP 已经全面支持双渲染引擎，可以在友空间上开发、使用 APICloud 小程序。
>

#### 1.2.1. 平台发展历程【初级】

- 《APICloud 开发平台介绍》 https://docs.apicloud.com/APICloud/LCDP

#### 1.2.2. 生态能力介绍【初级】
- 《APICloud 开发者生态》 https://docs.apicloud.com/APICloud/apicloud-developer

#### 1.2.4. 云平台基础【初级】

##### 1.2.4.1 应用设置

##### 1.2.4.2 快速设置证书

##### 1.2.4.3 云编译

- 《APICloud 控制台》http://www.apicloud.com/console

#### 1.2.5. 快速上手【初级】

- 《Hello APP》https://gitee.com/apicloud/hello-app
- 《新手开发指南》https://docs.apicloud.com/APICloud/junior-develop-guide
- 《创建第一个应用》https://docs.apicloud.com/APICloud/creating-first-app
- 《视频：入门新手必看》http://www.apicloud.com/video_play/15_1
- 《七天培训课》 https://docs.apicloud.com/Seven/Day1
- 《30 天 APP 开发从 0 到 1》https://github.com/apicloudcom/30-APP-0-1

#### 1.2.5. 多端演进介绍【初级】

- 《APICloud 3：AVM 多端开发简介》 https://docs.apicloud.com/apicloud3/
- 《友空间小程序开发教程》 https://docs.apicloud.com/Dev-Guide/Yonyou-zone-applet-development-tutorial

## 2.  端开发

> 在这一部分中，则开始简单使用平台进行主流程学习，也是正式成为移动端开发者的第一步。

### 2.1.  开发工具

> 为了更好地开发移动端应用，建议使用官方推出的专门的开发工具：APICloud Studio 3 。在【2.1. 开发工具】一节中会详细介绍工具的下载安装和功能使用。
>
> 跟随【2.1.2. 创建项目和认识项目结构】的内容，通过工具创建一个应用，会自动检出项目代码，介绍包结构和相关知识点。主要学习 Widget 包的内容。在《hello APP》中有介绍文件夹作用，并且标明了版本。另外，一个合法的 APICloud 应用，需要在根目录下有一个 config.xml 文件，用于配置应用的基本信息，所以也需要详细了解该文件的作用。
>
> 随后进行【2.1.3. 调试和预览】，以便查看应用的运行效果。
>
> 在【2.1.4 代码管理和编译】将会介绍如何稍作以修改代码，提交代码到云端，进行打包编译出成品。

#### 2.1.1. 下载安装工具【初级】

- 《APICloud Studio 3 的使用与说明》https://docs.apicloud.com/apicloud3/#/overview/devtools?index=0&subIndex=3
- 《下载 APICloud Studio 3》https://www.apicloud.com/studio3#downloadBtn
- 《视频教程：APICloud Studio 3的使用》http://www.apicloud.com/video_play/18_1
- 《APICloud Studio 3 快速入门》https://docs.apicloud.com/Dev-Tools/studio3-first-app

#### 2.1.2. 创建项目和认识项目结构【初级】

- 《Hello APP-包结构说明》https://gitee.com/apicloud/hello-app#313-%E5%8C%85%E7%BB%93%E6%9E%84%E8%AF%B4%E6%98%8E
- 《Widget 包结构说明》https://docs.apicloud.com/Dev-Guide/widget-package-structure-manual
- 《支持 AVM 的目录结构》https://docs.apicloud.com/apicloud3/#/basic/project?index=1&subIndex=0
- 《config.xml 配置说明》https://docs.apicloud.com/Dev-Guide/app-config-manual?uzchannel=30

#### 2.1.3. 调试和预览【初级】

- 《Hello APP - 调试和预览》https://gitee.com/apicloud/hello-app#4-%E8%B0%83%E8%AF%95%E5%92%8C%E9%A2%84%E8%A7%88
- 《开发工具文档：实时预览》https://docs.apicloud.com/apicloud3/#live-preview
- 《视频：WiFi 真机实时预览》http://www.apicloud.com/video_play/18_12

#### 2.1.4. 代码管理和编译【初级】

- 《开发工具文档：代码管理》https://docs.apicloud.com/apicloud3/#code-manager
-  《控制台：代码设置》http://www.apicloud.com/code
- 《文档：Git 代码托管指南》https://docs.apicloud.com/Dev-Guide/Git-APICloud-guide



### 2.2.  端 API

> 本部分是从初级到中级的过渡内容。在初步掌握 APICloud 开发基础以后，便开始系统地深入学习 APICloud 进阶内容。
>
> API 对象作为端 API 的核心内容，也是开发移动端应用的基础。通过学习文档，了解对象中包含的属性、事件和方法。

#### 2.2.1 API 对象【中级】

- 《文档：端 API - 属性/事件/方法》https://docs.apicloud.com/Client-API/api

### 2.3.  模块生态

> 【2.3.1 模块简介】中将介绍模块的基本情况：在跨平台应用开发中，有时候前端无法完成或者是复杂且难度大的情景下，例如在一个高频度交互的界面，或者是需要调用硬件能力的界面，都可以使用原生模块来完成。另外还有一些原生开发的第三方服务， 仅仅提供了原生的 SDK，也需要按照这样的模式来嵌入。
>
> 从类型上来说：模块可以分为设备访问、功能扩展、界面布局、导航菜单、开放SDK等等。
> 从来源上来说，又分为官方模块、第三方供应商和个人独立开发者模块。
>
> 【2.3.2 模块使用】方法非常简单，但仍然需要注意一些要点：可以在控制台中可以添加和删除模块。因为模块是属于原生基座内容，模块有更新和变化的时候，需要重新自定义 Loader 来更新基座的代码环境，所以需要进一步学习自定义 Loader 的相关知识要点。
>
> 另外，在市场中的一些模块需要二次修改或者调整资源后，以【2.3.3 自定义模块】的形式使用。在【2.5.1 自定义模块开发】则讲解了具备原生端开发能力的开发者，如何使用 APICloud 的模块机制，自主开发所需要的模块。开发完成以后，可以上架到模块 Store 市场，也可以通过自定义模块的方式，私有使用。

#### 2.3.1 模块简介【中级】

#### 2.3.2. 模块使用【中级】

#### 2.3.3. 自定义模块【高级】

- 《模块的使用步骤》（待补充）
- 《自定义 Loader 说明》https://docs.apicloud.com/Dev-Guide/Custom_Loader
- 《自定义模块说明》https://docs.apicloud.com/Module-Dev/Upload-custom-module



###  2.4. 应用类型和渲染模式

> 在这一部分，会为开发者讲述 APICloud 的两种渲染模式：使用 HTML 和 WEB 技术来开发的【2.4.1 WebView模式】和使用 STML 和 JS 等自定义 DSL 来开发的【2.4.2 AVM 模式】。
>
> WebView 模式是早些时候的基础模式，可以完整使用 Web 相关标准。AVM 模式则是原生渲染，且支持跨端编译。在 APP 环境下，两者可以共存，因为引擎是同时支持的。
>
> 在【2.4.1 WebView模式】中，【2.4.1.1 HTML 开发页面】将会演示如何使用 HTML 和原生 JS 进行开发一个 Hello APP。
>
> 【2.4.1.2 使用前端框架和库】中将演示如何使用 jQuery、api.js、Vue.js 等文件来进行多页面开发。
>
> 有能力的开发者，可以探索【2.4.1.3 前端工程化适配】，将先有的基于 Webpack 等其他现代前端构建工具与 APICloud 多页面模式相结合，享受快速移植的开发体验，现有丰富的组件库生态和 APICloud 的高性能原生体验，这是专家级的。
>
> 同时，开发者更应该关注【2.4.2 AVM 模式】的 APICloud 开发模式。APICloud 自 3.0 起，已从跨平台技术全面升级为多端技术：
> 1. 使用 avm.js 一个技术栈可同时开发 Android & iOS 原生 App、小程序和 iOS 轻 App，且多端渲染效果统一；
> 2. 全新的 App 引擎 3.0 不依赖 webView，提供百分百的原生渲染，保障 App 性能和体验与原生 App 一致。
> 3. 现有 api 直接映射兼容小程序接口，延续已有开发习惯。

> 在 AVM 开发中，则需要进行了解多端开发的【2.4.2.1 AVM 基础】，包括新的目录结构，事件属性数据绑定和指令等。也需要进行了解新的引擎中内置的对齐到 Web 标准的 API 接口。

> 需要了解常用系统组件。这也是为【2.4.2.2 组件化开发】奠定基础。开发者可以根据组件化相关机制，进行业务组件的高级封装。

> 另外【2.4.2.3 组件库开发中】指出专家级的开发者可以使用更高阶的模式，开发出普适性更高的通用组件（库）。

#### 2.4.1.  WebView 模式

##### 2.4.1.1. 使用 HTML 开发页面 【中级】

##### 2.4.1.2. 使用前端框架和库【高级】

##### 2.4.1.3. 前端工程化适配【专家】

- 《HTML 模式》https://docs.apicloud.com/Dev-Guide/Yonyou-zone-applet-development-tutorial
- 《APICloud 开发工具核心库》https://docs.apicloud.com/Dev-Tools/apicloud-tools-core
- 《脚手架：APICloud-cli 工具的使用说明》https://docs.apicloud.com/Dev-Tools/apicloud-cli
- 《社区方案：AVVW APICloud 开发框架》https://github.com/grapewheel/avvw

#### 2.4.2  AVM 模式

##### 2.4.2.1. AVM 概览和基础【中级】

##### 2.4.2.2. 多端 API【中级】

##### 2.4.2.3. 通用参考【中级】

##### 2.4.2.4. 系统组件【中级】

##### 2.4.2.5. 组件化开发【高级】

##### 2.4.2.6. 组件库开发【专家】

- 《文档：多端开发简介》https://docs.apicloud.com/apicloud3/
- 《AVM 体验代码》https://docs.apicloud.com/apicloud3/#/overview/samples?index=0&subIndex=2
- 《源码：avm-simple 组件示例代码》https://github.com/apicloudcom/avm-simple
- 《源码：多端案例合集》https://github.com/apicloudcom/mx-app-templates
- 《视频：90分钟开发一套APICloud多端模板APP+小程序》https://ke.qq.com/course/3133445?taid=10975578474663941
- 《AVM 组件开发规范》https://docs.apicloud.com/Module-Dev/Component-development-specification
- 《源码：ACT 组件库》https://github.com/apicloudcom/act



### 2.5. 原生进阶使用

> APICloud 是一款跨端跨平台的前端开发框架。旨在为前端开发者赋能移动多端开发能力。
>
> 在一些必要的复杂场景下，或者是的确需要原生能力的时候，具有原生开发能力的开发者也可以通过开放的模块开发机制来拓展应用能力。所以在【2.5.1自定义模块开发中】则介绍了这些相关知识。
>
> 除了模块的介入模式之外，部分原生应用也可以通过 SDK 的方式，把 APICloud 的整个引擎植入到原有应用中。在【2.5.2 SuperWebView 使用】一节中则是这种使用的相关资料。典型案例就是：友空间 APP 原来是不具备 APICloud 的能力的，在通过 SDK 融合以后，在友空间APP（v6.2.7+）里就可以使用 APICloud 引擎开发 APICloud 小程序了。

#### 2.5.1 自定义模块开发【专家】

- 《模块包结构说明》https://docs.apicloud.com/Dev-Guide/module-package-structure-manual
- 《模块 Store 规范》https://docs.apicloud.com/Module-Dev/Module-Store-Guide
- 《模块开发指南_iOS》https://docs.apicloud.com/Module-Dev/module-dev-guide-for-ios
- 《模块开发指南_Android_Studio》https://docs.apicloud.com/Module-Dev/module-dev-guide-for-android-studio
- 《模块开发指南_Android_Eclipse》https://docs.apicloud.com/Module-Dev/module-dev-guide-for-android
- 《视频：模块开发-Android》https://www.apicloud.com/video_play/16_1
- 《视频：模块开发-iOS》https://www.apicloud.com/video_play/6_1

#### 2.5.2. SuperWebView 使用【专家】

- 《SuperWebView 开发指南-Android》https://docs.apicloud.com/Dev-Guide/SuperWebview-guide-for-android
- 《SuperWebView 开发指南-iOS》https://docs.apicloud.com/Dev-Guide/SuperWebview-guide-for-ios
- 《APICloud CTO分享SuperWebView公开课》https://www.apicloud.com/video_play/3_1
- 《视频：SuperWebView 教程-Android》https://www.apicloud.com/video_play/9_1
- 《视频：SuperWebView 教程-iOS》https://www.apicloud.com/video_play/7_1

> 在学习了 APICloud 基础的端 API 对象和模块等开发知识以后，进一步学习 AVM 多端开发技术，再拓展一下原生相关知识，大致就可以开发出任何功能的形态的跨端应用了。
>
> 在此基础上，你需要了解更多的杂项和技术细节，让应用的体验更佳，性能更好。同时也需要了解一些技术和政策规范。

### 2.6. 端开发的进阶技术专题【高级】

- 《如何开发出优秀的APICloud应用》 https://docs.apicloud.com/APICloud/app-guide
- 《屏幕适配原理》https://docs.apicloud.com/Dev-Guide/screen-adapt-guide
- 《如何在APICloud平台使用腾讯X5引擎》https://docs.apicloud.com/Dev-Guide/X5-APICloud-guide
- 《APICloud 应用合规指南》https://docs.apicloud.com/Others/app-compliance-guide
- 《代码加密规范》https://docs.apicloud.com/Dev-Guide/Code-Specification
- 《常见 FAQ》https://docs.apicloud.com/Others/FAQ/Client-Dev



## 3. 云开发

> APICloud 推出了云端一体的概念和产品形态。能够快速使用数据云完成云端的数据存储和服务接口。
>
> 数据分为两个版本。初期是【3.1 数据云 1.0】版本，在这个版本中，拥有快速创建数据表的能力和自动生成 Rest 风格的请求接口。使用简单，上手容易。
>
> 随后，数据云也进行了升级，最新版本是【3.2 数据云 3.0】，这一版本的数据云功能更加强大，除了支持数据库和接口生成之外，还额外的支持了云函数功能，开发者可以在接口中自助开发后端逻辑，包括鉴权、模块等。另外还支持数据库访问模型，快速生成 ORM 等方式助力增删查改的逻辑开发。也支持文件上传和低代码自动生成的后台管理系统。

### 3.1. 数据云 1.0

#### 3.1.1. 数据云 1 模型【中级】

#### 3.1.2. Rest 接口和鉴权【中级】

- 《数据云 1.0 开发指南》https://docs.apicloud.com/Dev-Guide/data-cloud-dev-guide
- 《数据云 1.0 API 文档》https://docs.apicloud.com/Cloud-API/data-cloud-api
- 《云 API 的 SDK》https://docs.apicloud.com/Cloud-API/sdk-cloud-api

### 3.2. 数据云 3.0

#### 3.2.1. 数据云 3 配置【高级】

#### 3.2.2. 数据云 3 模型【高级】

#### 3.2.3. 云函数和文件上传【高级】

- 《数据云 3.0 的快速上手》https://gitee.com/apicloud/ordering-food/tree/main/docs#%E6%95%B0%E6%8D%AE%E4%BA%91%E6%A8%A1%E5%9E%8B%E5%AF%BC%E5%85%A5%E5%92%8C%E5%BF%AB%E9%80%9F%E4%B8%8A%E6%89%8B
- 《数据云 3.0 总文档》https://docs.apicloud.com/Cloud-API/sentosa



## 4. 云平台进阶

> 在前面的【1.2.4 云平台基础】中，走马观花式的把云平台的功能大致了解了一番。部分基础内容，诸如应用信息设置、云编译打包等功能需要在基础部分掌握。
>
> 另外在【2 端开发】的【2.3 模块生态】中，也需要使用云平台和模块 Store 等界面。
>
> 除此之外，云平台还有需要进阶功能，来完成移动端开发的完整流程。在本部分会提及【4.1 开发管理】，包括证书、代码和模块等。
>
> 还针对运营维护方面的开发者和相关人员准备了《4.2 运营管理》的内容，能够快速使用平台进行统计、消息、版本和热修复等。
>
> 同时针对企业版用户还有一些安全控制、企业商店来实现相关客户对业务的特殊要求。

### 4.1. 开发管理

#### 4.1.1. 证书管理【中级】

#### 4.1.2. 代码管理【中级】

#### 4.1.3. 模块管理【中级】

- 《证书管理界面》http://www.apicloud.com/certificate
- 《安卓证书指南》https://docs.apicloud.com/Dev-Guide/Android-License-Application-Guidance
- 《iOS 证书指南》https://docs.apicloud.com/Dev-Guide/iOS-License-Application-Guidance
- 《iOS 证书生成服务》https://developer.yonyou.com/forum.php?mod=viewthread&tid=170538&fromuid=722608

### 4.2. 运营管理

#### 4.2.1. 统计分析【高级】

#### 4.2.2. 消息推送【高级】

#### 4.2.3. 版本管理【高级】

- 《统计服务》http://www.apicloud.com/total
- 《推送服务》http://www.apicloud.com/push
- 《统计云 API》https://docs.apicloud.com/Cloud-API/stat-cloud-api
- 《推送技术指南》https://docs.apicloud.com/Dev-Guide/push-guide
- 《模块 Store：推送与 IM》https://www.apicloud.com/mod-sdk/ts
- 《版本管理使用指南》https://docs.apicloud.com/Dev-Guide/version_update
- 《云修复（热更新）使用指南》https://docs.apicloud.com/Dev-Guide/smartUpdate

### 4.3. 安全控制

- 《运行控制说明》https://docs.apicloud.com/Dev-Guide/app-control

### 4.4. 企业 App Store

- 《企业 Store 使用说明》https://docs.apicloud.com/Dev-Guide/App-Store

## 5. 其他资源

APICloud 开发过程中，遇到的知识点和难题都可以在官方文档和开发者论坛中找到相关信息。部分项目和模块也有 GitHub 相关开发者主页，有大量的开源项目和代码。针对国内访问不顺利的开发者来说，也可以访问 Gitee 码云。另外在腾讯课堂和 B 站也开设了相关官方主页，提供更多的视频资源。

- 《APICloud 官方文档》https://docs.apicloud.com/
- 《开发者社区》https://developer.yonyou.com/forum-2-1.html
- 《GitHub 主页》https://github.com/apicloudcom/
- 《Gitee 主页》https://gitee.com/apicloud
- 《腾讯课堂主页》https://apicloud.ke.qq.com/
- 《Bilibili 主页》https://space.bilibili.com/627080013












