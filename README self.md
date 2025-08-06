<!--
 * @Description: 
 * @Author: zhangweijuan
 * @Date: 2025-08-06 08:57:25
 * @LastEditTime: 2025-08-06 09:08:11
-->
# focus-flow

## 介绍

focus-flow 是一个基于 [taro+vue3]构建的专注、待办工具。

## 安装
### first step

```bash
taro init taro-vue-demo focus-flow
  choose Vue3
  TypeScript
  Sass
  Pnpm 
  Vite
```

### second step

```bash
pnpm install
```

### third step

```bash
pnpm run dev:weapp
```

## 使用

在config/index.ts中修改配置，多端打包后不会覆盖其它端配置
```jsx
outputRoot: `dist/${process.env.TARO_ENV}`,
```