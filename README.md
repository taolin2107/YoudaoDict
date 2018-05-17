# YoudaoDict

自制有道词典 Chrome 扩展，使用[有道词典 api](http://fanyi.youdao.com/openapi)

## 安装

* 去 [Chrome 官方商店](https://chrome.google.com/webstore/detail/youdao-dict/geboigdomoihijcamklnhlcgnnpdgkmg)安装。
* 下载 [crx 文件](https://github.com/youngdze/YoudaoDict/releases)安装。

## 申请有道智云app key

1. 去[有道智云](http://ai.youdao.com/index.s) -> 自然语言翻译 -> 翻译实例 -> 创建实例 -> 文本翻译服务

2. 去[有道智云](http://ai.youdao.com/index.s) -> 应用管理 -> 我的应用 -> 创建应用 -> 绑定服务 -> 选择步骤1创建的文本翻译服务 -> 获取此应用的`应用ID`和`应用密钥`

3. 将步骤2获取的`应用ID`和`应用密钥`，填入到`src/script/util/youdao.js`中的`appkey`和`appsecret`

## 开发

```shell
npm install
npm run dev
```

在 Chrome 扩展页面点击载入开发中的扩展，选择 `build` 目录。

## Test

```shell
npm run test
```

## 功能

* 点击扩展图标输入进行翻译
* 双击或按设置的按键(默认为 CTRL)对选择区域进行翻译
* 添加生词至有道单词本
* 添加个人有道词典 key

## 版权 LICENSE

* MIT
