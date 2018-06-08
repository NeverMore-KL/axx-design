

# Axx Design

## 安装

```bash
npm install axxd --save
```

## 示例

```jsx
import { DatePicker } from 'axxd';
ReactDOM.render(<DatePicker />, mountNode);
```

引入样式：

```jsx
import 'axxd/dist/axxd.css';  // or 'axxd/dist/axxd.less'
```


## 本地开发

```bash
$ git clone https://github.com/gaosife/axx-design.git
$ cd axx-design
$ npm install
$ npm run start
```

打开浏览器访问 http://127.0.0.1:8001 

### 调整组件样式
> 在调整现有组件样式时，优先修改现有全局样式变量，若现有变量不满足可调整组件内部样式。

[全局样式变量](https://github.com/gaosife/axx-design/blob/f5fa5a77755b3202aef2e31660026d5c1fa228be/components/style/themes/default.less)

## Test Case and Lint

### Run all test cases
``` bash
$ npm test -- -u
```

### Run test cases for one file
```bash
$ npm test -- components/button/__tests__/index.test.js
```

## Publish site to gh-pages
```bash
$ npm run site
```

## 分支管理
- master   主分支  
- pub_dev  预发布
- dev      开发
