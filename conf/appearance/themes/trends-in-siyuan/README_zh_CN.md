一个模仿 Trends 系列期刊样式的主题，总体设计简洁学术。通过超级块配置边栏后能达到和期刊原文非常相似的效果。

## 基本特点

- Trends 期刊正文样式
    - 配色风格
    - 表格样式
    - 图标 caption 颜色
- 文档顶部显示 banner
- 表格默认居中
- 自定义属性: 设置 `paper-part` 为 `abstract`, 会将段落按照摘要的样式显示
    - 字体加粗
    - 颜色为蓝色

## 说明

题目上方的 `Trends in SiYuan` 为 svg 伪元素，原图使用 drawio 绘制，在源码 src 目录下可见。

如果不希望显示这个条幅，可以设置以下 css 代码片段:

```css
.protyle-title::before, .protyle-title::after {
    display: none;
}

.protyle-title>div[contenteditable] {
    margin-top: unset;
}
```
