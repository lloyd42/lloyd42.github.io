# Markdown Badge 使用入门

如果你打开一个热门开源的 ``GitHub`` 仓库，那么大概率就会看到很多五颜六色的 ``Badge`` 用于显示仓库的技术栈、统计、版本等等信息，看起来很酷。

下面将介绍如何获取这些以及如何自定义，来制作自己的 ``Badge``吧！

## 预制品

在这个网站 [md-badges](https://inttter.github.io/md-badges/)，你可以找到一大堆流行元素的 ``Badge`` 预制品。

预制品其实就是通过自定义制作好的，那么下面就介绍如何制作自己的专属 ``Badge`` 。

## 自定义

[shields.io](https://shields.io/badges) 提供简单、易用的 ``Badge`` 制作服务。

下面介绍如何制作 ``Static Badge``。

### 样式一

标签、信息和颜色用破折号分隔。例如：

[![shields.io](https://img.shields.io/badge/any_text-you_like-blue)](https://shields.io/badges)

语法：``https://img.shields.io/badge/{label}-{message}-{color}``

例子：<https://img.shields.io/badge/any_text-you_like-blue>

```md
[![shields.io](https://img.shields.io/badge/any_text-you_like-blue)](https://shields.io/badges)
```

### 样式二

只有信息和颜色，用破折号隔开。例如：

[![shields.io](https://img.shields.io/badge/just%20the%20message-8A2BE2)](https://shields.io/badges)

语法：``https://img.shields.io/badge/{message}-{color}``

例子：<https://img.shields.io/badge/just%20the%20message-8A2BE2>

```md
[![shields.io](https://img.shields.io/badge/just%20the%20message-8A2BE2)](https://shields.io/badges)
```

### 样式三

标签、信息和颜色用破折号分隔，``logo`` 定义使用 ``query`` 参数。例如：

[![Debian](https://img.shields.io/badge/Debian-debian-A81D33?logo=debian&logoColor=fff)](https://shields.io/badges)

语法：``https://img.shields.io/badge/{label}-{message}-{color}?logo={slug}&logoColor={color}``

例子：<https://img.shields.io/badge/Debian_debian-A81D33?logo=debian&logoColor=fff>

```md
[![shields.io](https://img.shields.io/badge/any_text-you_like-blue)](https://shields.io/badges)
```

通过这个 [icon网站](https://simpleicons.org/) 可以找到想要的 ``icon`` 和它对应的 ``color``

## 了解更多

- <https://shields.io/badges/static-badge>
- <https://simpleicons.org/>
- <https://inttter.github.io/md-badges/>

```md
This message is used to verify that this feed (feedId:72808323002484736) belongs to me (userId:68270158418253824). Join me in enjoying the next generation information browser https://follow.is.
```

<style module>
  p:has(a):not(:has(code)) {
    display: flex;
  }
  a:has(img) {
    margin-left: 5px;
  }
</style>
