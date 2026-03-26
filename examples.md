---
layout: page
title: 示例代码
---

# 示例代码

## Python 示例

```python
def greet(name):
    """问候函数"""
    print(f"你好, {name}!")

# 调用示例
greet("世界")
```

## JavaScript 示例

```javascript
// 异步函数示例
async function fetchData(url) {
  try {
    const response = await fetch(url);
    const data = await response.json();
    return data;
  } catch (error) {
    console.error('错误:', error);
  }
}
```

## 引用块

> 这是一段引用文字。
> 
> 可以包含多行。

## 任务列表

- [x] 完成文档编写
- [x] 添加示例代码
- [ ] 测试所有功能
- [ ] 部署到生产环境

---

*相关文档：[API 参考](api.md)*
