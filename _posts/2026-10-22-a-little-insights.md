---
layout: single
title: "A little insights"
excerpt_separator: "<!--more-->"
categories:
  - blog
tags:
  - update
  - insights
toc: true
toc_label: "文章目录"
toc_sticky: true
math: true
---

这里写文章的开头。这个标记之前的内容会作为自动摘要。

<!--more-->

## 一、文字与换行

这是普通文字，可以使用 **粗体**、*斜体* 和 `行内代码`。

这是第二段。两段之间空一行。

如果只想换行，不想另起一个段落：<br>
这一句会显示在下一行。

### 小标题

文章标题已经由主题显示，正文通常从二级标题开始。

## 二、链接、列表与引用

[Jekyll 官方网站](https://jekyllrb.com/)

- 第一个要点
- 第二个要点
- 第三个要点

1. 第一步
2. 第二步
3. 第三步

> 这里可以写引用，或者想强调的一句话。

## 三、图片

![描述图片内容]({{ '/assets/images/IMG_3013.JPG' }})

调整图片宽度并居中：

![居中的图片]({{ '/assets/images/bio-photo.jpg' }}){: .align-center width="480"}

带图片下方说明文字的版本：

{% include figure image_path="/assets/images/bio-photo.jpg" alt="描述图片内容" caption="这里是图片下方的说明文字。" %}

## 四、GIF 与表情

GIF 的插入方法和普通图片一样：

<!--
![开心的动图]({{ '/assets/images/happy.gif' | relative_url }})

如果想作为小表情插在文字里：

今天的心情：<img src="{{ '/assets/images/happy.gif' | relative_url }}" alt="开心" width="40" height="40" style="vertical-align: middle;">

普通 Emoji 可以直接输入：😊 🎉 ✨ 🐱

## 五、视频

### Bilibili 视频

将 YOUR_BV_ID 替换为视频的 BV 号：

{% include video id="YOUR_BV_ID" provider="bilibili" %}

### YouTube 视频

将 YOUR_VIDEO_ID 替换为视频 ID：

{% include video id="YOUR_VIDEO_ID" provider="youtube" %}

### 自己上传的 MP4

<video controls playsinline preload="metadata" style="width: 100%; height: auto;">
  <source src="{{ '/assets/videos/demo.mp4' | relative_url }}" type="video/mp4">
  你的浏览器不支持视频播放。
</video>
-->
## 六、代码

句子中的代码：运行 `print("Hello, world!")`。

多行代码使用三个反引号，并注明语言：

```python
def greet(name):
    return f"Hello, {name}!"

print(greet("world"))
```

```bash
bundle exec jekyll serve
```

## 七、数学公式

本节需要先完成下方的公式配置。

行内公式：能量与质量的关系是 $$E = mc^2$$。

独立成行的公式：

$$
\frac{a}{b} + \sqrt{x^2 + y^2} = z
$$

求和公式：

$$
\sum_{i=1}^{n} i = \frac{n(n+1)}{2}
$$

## 八、表格

| 元素 | 写法或用途 |
| --- | --- |
| 图片 | 展示照片、截图 |
| GIF | 展示动画、表情 |
| 代码 | 展示程序 |
| 公式 | 展示数学表达式 |

## 九、提示框

**提示：** 这里可以写一段补充说明。
{: .notice--info}

---

这里写文章的结尾。
