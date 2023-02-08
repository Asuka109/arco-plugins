## 1.4.8

`2023-02-08`

🐛 BugFix

- 修复 babel 自定义配置的问题


## 1.4.4

`2022-10-19`

🐛 BugFix

- 修复样式加载中的 `!` 识别问题


## 1.4.2

`2022-09-28`

💎 Enhancement

- 优化在用户已存在 babel-loader 时，直接修改babel 配置，而非引入新的 loader

🐛 BugFix

- 修复插件引入导致用户自定义 babel  插件无法获取到源码路径的 bug


## 1.4.1

`2022-06-22`


💎 Enhancement

- 内置对 `pnpm` 的路径格式的适配

## 1.4.0

`2022-06-22`


💎 Enhancement

- `include` 和 `varsInjectScope` 支持正则表达式。
  
## 1.3.1

`2022-03-18`


🐛 BugFix

- 使用 pnpm 时导入主题失败
  
## 1.3.0

`2022-03-17`

### 🆕 新增功能

- 属性 `themeOption` 替换为  `varsInjectScope`
  
## 1.2.0

`2022-03-17`

### 🆕 新增功能

- 新增属性 `themeOption`
  
## 1.1.2

`2022-02-21`


🐛 BugFix

- `transform-loader` 应该在 `ts-loader` 之后才加载

## 1.1.1

`2022-02-15`


🐛 BugFix

- 修复 getCompilationHooks 不存在的问题

## 1.1.0

`2022-02-14`

### 🆕 新增功能

- 支持通过 `webpackImplementation` 指定使用的 webpack 实例

🐛 问题修复

- 修复找不到 `@babel/preset-typescript` 的问题
