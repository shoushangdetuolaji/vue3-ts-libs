# vue-next-libs

> 向会js的云师兄学习的一个库，我是非原创开源精神，只想给自己锻炼，感谢作者

## 技术栈

- vue3
- ts
- scss
- ant



## 前期工作

- 个人项目没有eslint规则

- vue-cli 开发 css相关的预处理器

  >  [style-resources-loader](https://github.com/yenshih/style-resources-loader)
  >
  > https://cli.vuejs.org/zh/guide/css.html#%E8%87%AA%E5%8A%A8%E5%8C%96%E5%AF%BC%E5%85%A5

  有效解决css变量的引入问题，在vue.config.js配置

  ` vue add style-resources-loader`

   ```js
   module.exports = {
     pluginOptions: {
       'style-resources-loader': {
         preProcessor: 'scss',
         patterns: ['./src/assets/styles/variable.scss']
       }
     }
   }
   ```



## vue3新东西点

组件防止多层attrs

```: f
inheritAttrs: false 
```

