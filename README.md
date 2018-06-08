

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
- master   
- pub_dev  预发布
- dev      开发
