---
sidebar_label: 示例
hide_title: true
hide_table_of_contents: false
sidebar_position: 0
pagination_next: null
pagination_previous: null
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

# 示例

### Header
```
sidebar_label: 左侧标题
title: 标题
hide_table_of_contents: true //隐藏右侧导航
pagination_next: null //不设置下一页
pagination_previous: null //不设置上一页
sidebar_position: 0 //顺序
```

### Tab

<Tabs groupId="non-mac-operating-systems" lazy>
  <TabItem value="linux" label="Linux">

升级golang版本

```shell
sudo rm -rf /usr/local/go
```

然后用上面的方法安装最新版本即可

</TabItem>
  <TabItem value="mac" label="Mac">
  通过brew安装golang

```shell
brew install go
```

升级golang版本

```shell
brew upgrade go
```
  </TabItem>
</Tabs>


### Table

| 属性            | 类型              | 描述                                                         |
| :-------------- | :---------------- | :----------------------------------------------------------- |
| from            | obj               | 基础值,可选                                                  |
| loop            | obj/fn/bool       | 循环设置,请参[阅循 prop](#loop-prop)具了解更多详情           |
| delay           | number/fn         | 动画开始前的延迟毫秒.也可以是一个函数:key => delay          |
| reverse         | bool              | 如果设置为true,"from"和"to"会切换,这仅与"reset"标志结合使用才有意义 |
| pause           | bool              | `pause` prop可以及时冻结动画                                 |

### Tip

:::note

Some **content** with _markdown_ `syntax`. Check [this `api`](#).

:::

:::info

Some **content** with _markdown_ `syntax`. Check [this `api`](#).

:::

:::tip

Some **content** with _markdown_ `syntax`. Check [this `api`](#).

:::

:::caution

Some **content** with _markdown_ `syntax`. Check [this `api`](#).

:::

:::danger

Some **content** with _markdown_ `syntax`. Check [this `api`](#).

:::