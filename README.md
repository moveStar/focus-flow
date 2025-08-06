# focus-flow

## 介绍

focus-flow 是一个基于 [taro+vue3]构建的专注、待办工具。

## 安装

```bash
npm install focus-flow
```

## 使用

```jsx
import React from 'react';
import { FocusFlow } from 'focus-flow';

const Flow = () => {
  const elements = [
    {
      id: '1',
      type: 'input', // input node
      data: { label: 'Node 1' },
      position: { x: 250, y: 5 },
    },