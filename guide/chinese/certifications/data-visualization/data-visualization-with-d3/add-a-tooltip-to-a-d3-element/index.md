---
title: Add a Tooltip to a D3 Element
localeTitle: 将工具提示添加到D3元素
---
## 将工具提示添加到D3元素

### 提示 1

使用`.append()`方法。

### 提示 2

使用`.text()`方法。

### 提示 3

链接`.append()`和`.text()`方法。

### 提示 4

在` .text() `方法中使用回调函数。

### 答案

使用`svg.selectAll("rect")`方法链接以下代码行。

```javascript
  .append("title")
  .text(d=>d);
```