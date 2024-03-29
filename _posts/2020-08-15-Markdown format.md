---
title: Markdown format
---

主题使用 GitHub 官方语法，样式也是遵循 GitHub 风格，如下：

## 1. 图片

![图片样例]({{ site.img }}/example.jpg)

## 2. 引用

> 我思故我在 -- 笛卡尔

## 3. 代码段

```c++
#include <iostream>

using namespace std;

int main(){
  cout << "Hello World!";
  return 0;
}
```

## 4. 字体

- **粗体**
- _斜体_
- `高亮`
- ~~删除~~
- <u>下划线</u>

## 5. 表格

| name  | ID  | score |
| ----- | --- | ----- |
| David | 1   | 98    |
| Nancy | 2   | 99    |
| Curry | 3   | 101   |

## 6. 数学公式

如果你的文章需要数学公式渲染，添加 `Liquid` 标签 {% raw %} `{{ site.math }}` {% endraw %} 到文章末尾。

$$
\frac{\mathrm{d}}{\mathrm{d}t} \left ( \frac {\partial L}{\partial \dot{q}_j} \right ) = \frac {\partial L}{\partial q_j}
$$

## 7. 视频

<video src="https://cdn-video.xinpianchang.com/5b7fc02a84108.mp4" width = "100%" controls preload></video>

## 8. 表情

GitHub 官方支持了一些 Jekyll 插件，具体查看 <https://pages.github.com/versions/>，表情可以直接使用输入法的表情，也可以使用 GitHub 生成的表情

:smile:

## 9. mentions

这也是 GitHub 提供的 Jekyll 插件，只需要在 GitHub 用户名之前加个 `@` 即可。如下

@professordeng

## 10. GitHub 头像

通过 GitHub 提供的 Jekyll 插件，我们可以生成 GitHub 用户的头像，如下：

{% avatar professordeng %}
{% avatar ericclose %}

{{ site.math }}
