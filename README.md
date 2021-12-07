<div id="top"></div>

<div style="text-align: center">
<img src="https://img.shields.io/badge/LICENSE-MIT-brightgreen" style="margin-right: 4px" />
<a href="https://www.npmjs.com/package/@tuya-sat/components"><img src="https://img.shields.io/badge/npm-v0.0.2-brightgreen" /></a>
</div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <img src="https://images.tuyacn.com/rms-static/e8c393e0-4b6e-11ec-bf56-238df7ae6cb1-1637570026526.png?tyName=SATURN%20MOONS.png" alt="Logo" width="80" height="80">

  <h3 align="center">SatComponents</h3>

  <p align="center">
    SaaS微应用组件库
    <br /> 
    <br />
    <a href="https://github.com/tuya-sat/discuss/blob/maxbbn-patch-1/README.md">土星项目</a>
    ·
    <a href="https://github.com/tuya-sat/discuss/issues">报告问题</a>
    ·
    <a href="https://github.com/tuya-sat/discuss/issues">提交需求</a>    
  </p>
  <img src="https://images.tuyacn.com/rms-static/b9326810-5409-11ec-89bb-d7b7de210e4b-1638516128017.png?tyName=desc.png" style="width: 100%;">
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>目录</summary>
  <ol>
    <li><a href="#介绍" target="_self">介绍</a></li>
    <li><a href="#安装" target="_self">安装</a></li>
    <li><a href="#使用" target="_self">使用</a></li>
    <li><a href="#配置" target="_self">配置</a></li>
    <li><a href="#生态" target="_self">生态</a></li>
    <li><a href="#浏览器兼容性" target="_self">浏览器兼容性</a></li>
    <li><a href="#组件看板" target="_self">组件看板</a></li>
    <li><a href="#联系我们" target="_self">联系我们</a></li>
    <li><a href="#License" target="_self">License</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## 介绍

组件库则是基于 Ant Design 而开发的模版组件。 服务于涂鸦开发者 SaaS，帮助开发者提升页面的开发效率，更快的落地 [微应用](https://github.com/tuya-sat/discuss/blob/maxbbn-patch-1/Intro.md) 页面。

<!-- GETTING STARTED -->

## 安装

```shell
yarn add @tuya-sat/components
```

<!-- USAGE EXAMPLES -->

## 使用

依赖 Antd 4.16.13 React >=16.0.0

```
import { ImagePreview } from '@tuya-sat/components';
```

## 配置

在`.babelrc`文件中添加

```json5
{
  plugins: [
    [
      'import',
      {
        libraryName: 'antd',
        libraryDirectory: 'es',
        style: 'css',
      },
      'antd',
    ],
    [
      'import',
      {
        libraryName: '@tuya-sat/components',
        libraryDirectory: 'es',
        style: 'css',
      },
      '@tuya-sat/components',
    ],
  ],
}
```

## 生态

| 项目                          | 版本                                                                                  | 备注                   |
| ----------------------------- | ------------------------------------------------------------------------------------- | ---------------------- |
| @tuya-sat/create-micro-app    | [![create-micro-status]](https://www.npmjs.com/package/@tuya-sat/create-micro-app)    | 微应用模板生成工具     |
| @tuya-sat/sdf-cli             | [![create-micro-status]](https://www.npmjs.com/package/@tuya-sat/sdf-cli)             | 微应用上传打包         |
| @tuya-sat/micro-dev-component | [![create-micro-status]](https://www.npmjs.com/package/@tuya-sat/micro-dev-component) | 控制微应用角色权限     |
| @tuya-sat/micro-dev-loader    | [![create-micro-status]](https://www.npmjs.com/package/@tuya-sat/micro-dev-loader)    | 模拟主应用方法         |
| @tuya-sat/micro-dev-proxy     | [![create-micro-status]](https://www.npmjs.com/package/@tuya-sat/micro-dev-proxy)     | 模拟主应用接口转发     |
| @tuya-sat/micro-script        | [![create-micro-status]](https://www.npmjs.com/package/@tuya-sat/micro-script)        | webpack 自定义打包配置 |

[create-micro-status]: https://img.shields.io/badge/npm-v0.0.1--beta-brightgreen

## 🖥 浏览器兼容性

现代浏览器和 Internet Explorer 11 (with [polyfills](https://stackoverflow.com/questions/57020976/polyfills-in-2019-for-ie11))

| [![edge](https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png)](http://godban.github.io/browsers-support-badges/) | [![Edge](https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png)](http://godban.github.io/browsers-support-badges/) | [![chrome](https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png)](http://godban.github.io/browsers-support-badges/) | [![safari](https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png)](http://godban.github.io/browsers-support-badges/) |
| ------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| IE11, Edge                                                                                                                                        | last 2 versions                                                                                                                                         | last 2 versions                                                                                                                                         | last 2 versions                                                                                                                                         |

## 组件看板

| 组件               | 简介         |
| ------------------ | ------------ |
| Cascader           | 级联选择     |
| Excaption          | 异常页       |
| ImagePreview       | 图片展示     |
| Pagination         | 分页         |
| ResizeBox          | 伸缩盒子     |
| Tabs               | 标签页       |
| Text               | 文字         |
| Tree               | 树           |
| Form               | 高级表单     |
| Search             | 搜索表单     |
| SearchTable        | 搜索表格     |
| Table              | 表格         |
| Layout             | 布局         |
| RelateDeviceLayout | 关联设备布局 |
| TreeLayout         | 树布局       |
| TwoColumnLayout    | 两列布局     |
| SatConfigProvider  | 全局化配置   |

## 联系我们

欢迎在 https://github.com/tuya-sat/discuss/issues 向我们提交反馈

## License

MIT
