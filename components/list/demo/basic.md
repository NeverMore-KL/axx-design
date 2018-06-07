---
order: 1
title:
  zh-CN: 基础列表
  en-US: Basic list
---

## zh-CN

基础列表。

## en-US

Basic list.

````jsx
import { List, Avatar } from 'axxd';

const data = [
  {
    title: 'Axx Design Title 1',
  },
  {
    title: 'Axx Design Title 2',
  },
  {
    title: 'Axx Design Title 3',
  },
  {
    title: 'Axx Design Title 4',
  },
];

ReactDOM.render(
  <List
    itemLayout="horizontal"
    dataSource={data}
    renderItem={item => (
      <List.Item>
        <List.Item.Meta
          avatar={<Avatar src="https://zos.alipayobjects.com/rmsportal/ODTLcjxAfvqbxHnVXCYX.png" />}
          title={<a href="https://ant.design">{item.title}</a>}
          description="Axx Design, a design language for background applications, is refined by Ant UED Team"
        />
      </List.Item>
    )}
  />
, mountNode);
````
