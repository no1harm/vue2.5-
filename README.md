### **进行vue应用开发**
主要目的：学习vue开发以及了解整个前端工程的开发流程

**项目环境配置**
`node v10.1.0` + `npm 5.5.0` + `vue-cli 2.9.6`

`main.js`中引入`import './assets/styles/reset.css'`重置样式  `import './assets/styles/border.css'`解决移动端像素边框问题


**项目触及知识点**

- `rem`
根据网页的根元素来设置字体大小，和em（font size of the element）的区别是，em是根据其父元素的字体大小来设置，而rem是根据网页的跟元素（html）来设置字体大小的

- 使用`iconfont`
`iconfont`创建项目 -> 收集图标 -> 打包下载 -> 复制到项目相关文件夹 -> 修改`iconfont.css`中文件路径 -> 项目`main.js`引用 -> 复制图标代码 -> `<span class="iconfont">&#xe624;</span>` -> 引用成功

- 使用`git branch`分支开发功能

- 使用`awesome swiper`创建轮播图
[github](https://github.com/surmon-china/vue-awesome-swiper) -> `awsom swiper` -> `npm install vue-awesome-swiper --save`