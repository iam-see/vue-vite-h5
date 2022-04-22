# H5 模板

## 特性

- ⚡️ [Vue 3](https://github.com/vuejs/vue-next), [Vite 2](https://github.com/vitejs/vite) - 快！
- 💪 [Typescript](https://www.typescriptlang.org/) - 当然！必不可少
- 🎉 [Vant 3](https://vant-contrib.gitee.io/vant/#/zh-CN) - 基于 Vue.js 3 的轻量、可靠的移动端 Vue 组件库
- 🔥 [Axios 配置和封装](https://github.com/axios/axios) - 基于 Promise 的 HTTP 请求库
- 💡 [Vue Router 4](https://router.vuejs.org/zh/) - Vuejs 的官方路由
- 📦 [组件自动按需加载](https://github.com/antfu/unplugin-vue-components) - 自动按需注册组件, 无需 import
- 📥 [API 自动按需加载](https://github.com/antfu/unplugin-auto-import) - 无需手动 import 进行引入
- 🍍 [Pinia 状态管理](https://pinia.esm.dev/) - 你将会喜欢上的 Vue Store
- 🎨 [Windi CSS](https://github.com/windicss/windicss) - 下一代实用的原子 css 框架
- 😃 [icones](https://github.com/antfu/unplugin-icons) - 强大的图标库，各种图标集为你所用
- 🌍 [I18n 国际化开箱即用](./locales) - 想要翻译？是的，都可以！
- 👩‍🎨 [NProgress](https://github.com/rstacruz/nprogress) - 页面加载进度反馈
- 😃 [SVG 支持](https://github.com/jpkleemans/vite-svg-loader) - 支持以 组件形式使用 SVG 图片
- 📑 [Markdown 支持](https://github.com/antfu/vite-plugin-md) - 随意的在页面中嵌入 Markdown
- 🔑 完整支持的代码风格规范和代码提交规范

## 已配置

### UI 框架

- [Windi CSS](https://github.com/windicss/windicss) (按需的 [TailwindCSS](https://tailwindcss.com/)) - 更轻，更快和和一系列额外的特性!
  - [Windi CSS Typography](https://windicss.org/plugins/official/typography.html)
- [Vant](https://vant-contrib.gitee.io/vant/#/zh-CN) - 基于 Vue.js 3 的轻量、可靠的移动端组件库

### Icons

- [🔍Icônes](https://icones.netlify.app/) - 使用任意的图标集
  - [unplugin-icons](https://github.com/antfu/unplugin-icons) - 自动按需引入你所需要的图标！

### 插件

- [Vue Router 4](https://router.vuejs.org/zh/) - Vuejs 的官方路由
- [Pinia](https://pinia.esm.dev) - 新一代的 Vue Store 状态管理
- [Axios](https://github.com/axios/axios) - 基于 Promise 的 HTTP 请求库
- [unplugin-vue-components](https://github.com/antfu/unplugin-vue-components) - 自动按需加载组件
- [ "](https://github.com/antfu/unplugin-auto-import) - 自动按需加载 API
- [vite-plugin-windicss](https://github.com/antfu/vite-plugin-windicss) - Windi CSS 的整合
- [vite-plugin-md](https://github.com/antfu/vite-plugin-md) - Markdown 作为组件，也可以让组件在 Markdown 中使用
  - [markdown-it-prism](https://github.com/jGleitz/markdown-it-prism) - [Prism](https://prismjs.com/) 的语法高亮
  - [prism-theme-vars](https://github.com/antfu/prism-theme-vars) - 利用 CSS 变量自定义 Prism.js 的主题
  - [markdown-it-link-attributes](https://github.com/crookedneighbor/markdown-it-link-attributes) - 统一设置 Markdown 里的超链接跳转方式
- [Vue I18n](https://github.com/intlify/vue-i18n-next) - 国际化
  - [vite-plugin-vue-i18n](https://github.com/intlify/vite-plugin-vue-i18n) - Vue I18n 的 Vite 插件
- [vite-plugin-fonts](https://github.com/stafyniaksacha/vite-plugin-fonts) - Vite 的字体加载器
- [VueUse](https://github.com/antfu/vueuse) - 实用的 Composition API 工具合集
- [vite-svg-loader](https://github.com/jpkleemans/vite-svg-loader) - 支持以 组件形式使用 SVG 图片
- [vite-plugin-optimize-persist](https://github.com/antfu/vite-plugin-optimize-persist) - 允许你在 vite 中显式设置依赖项

### 编码风格

- [ESLint](https://eslint.org/) 配置为 [Airbnb Style](https://github.com/airbnb/javascript)

### 开发工具

- [TypeScript](https://www.typescriptlang.org/)
- [VS Code 扩展](./.vscode/extensions.json)
  - [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar) - Vue 3 IDE 支持
  - [Iconify IntelliSense](https://marketplace.visualstudio.com/items?itemName=antfu.iconify) - 图标内联显示和自动补全
  - [i18n Ally](https://marketplace.visualstudio.com/items?itemName=lokalise.i18n-ally) - 多合一的 I18n 支持
  - [Windi CSS 智能感知](https://marketplace.visualstudio.com/items?itemName=voorjaar.windicss-intellisense) - Windi CSS 的 IDE 支持
  - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - 代码质量和规则检查
  - [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - 专注于代码格式化、美化代码
  - [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) - 编码风格检查

## 清单

使用此模板时，请尝试按照清单正确更新你自己的信息

- [ ] 在 `package.json` 中改变作者名
- [ ] 在 `.env` 中改变标题
- [ ] 在 `public` 目录下改变 favicon
- [ ] 整理 `README `并删除路由

### 开发

只需要执行以下命令就可以在 http://localhost:8080 中看到

```bash
npm run dev
```

### 构建

构建该应用只需要执行以下命令

```bash
npm run build
```

然后你会看到用于发布的 `dist` 文件夹被生成。
