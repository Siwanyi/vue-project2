# vue3-event-admin

## Project introduction
该项目是一个个人文章发布与管理系统，主要包括文章分类、文章管理和个人中心三大模块。用户在注册、登录账号后进入该系统，可在文章分类中添加或移除分类，在文章管理中选择分类发布文章，同时文章信息会更新到页面，用户可对文章进行编辑或删除操作；在个人中心用户可进行基本资料修改，包括头像更换、密码重置等。
技术栈：Vue3 + create-vue（vite）+ Element-plus + axios
功能实现：
Vue3框架下，利用Element-plus完成页面响应式布局。利用vue-router相关技术实现页面路由的配置，并设置路由懒加载进行优化
axios二次封装，包括错误拦截、常用请求封装，全局请求loading，完成api请求模块封装。
使用pinia做数据状态管理，利用persistedstate插件实现持久化。
使用了pnpm包管理器，使用husky、lint-staged提交规范信息，使用Prettier统一格式化代码，集成Eslint代码校验规范。

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
pnpm install
```

### Compile and Hot-Reload for Development

```sh
pnpm dev
```

### Compile and Minify for Production

```sh
pnpm build
```

### Lint with [ESLint](https://eslint.org/)

```sh
pnpm lint
```
