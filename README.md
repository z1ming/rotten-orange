## Rotten Orange 仿造 ANTD 组件库
## 使用 React+typescript 实现自己的组件库

rotten orange 是一个组件库，使用 React Hooks 和 typescript 从零到一实现。


### 按照如下方法安装

~~~javascript
npm install rottenorange --save
~~~

### 使用

~~~javascript
// 加载样式
import 'rottenorange/dist/index.css'
// 引入组件
import { Button } from 'rottenorange'
~~~

### 项目亮点

* 🔥typescript with React Hooks
* ⛑️使用 react-testing-library 完成单元测试
* 📚使用 storybook 本地调试和生成文档页面
* 📚使用 react-doc-gen 自动生成文档
* 📦使用第三方库扩充组件-(react-fontawesome, react-transition-group)
* 🌹样式（Sass）文件从零开始，掌握大型应用的 CSS 组织方法
* 🎉涉及全部流程，包括最后的 npm publish，husky提交发布前验证，travis CI/CD 集成，发布文档站点等

### 一些本地开发命令

~~~bash
//启动本地环境
npm run stroybook

//跑单元测试
npm test

//build可发布静态文件
npm run build

//发布到 npm
npm run publish
~~~