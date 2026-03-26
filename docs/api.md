---
layout: page
title: API 参考
---

# API 参考

## 用户 API

### 获取用户信息

```http
GET /api/users/{id}
```

**响应示例：**

```json
{
  "id": 1,
  "name": "张三",
  "email": "zhangsan@example.com"
}
```

### 创建用户

```http
POST /api/users
Content-Type: application/json

{
  "name": "李四",
  "email": "lisi@example.com"
}
```

## 数据类型

| 类型 | 描述 | 示例 |
|------|------|------|
| string | 字符串 | "hello" |
| number | 数字 | 42 |
| boolean | 布尔值 | true |
| array | 数组 | [1, 2, 3] |
| object | 对象 | {"key": "value"} |

## 数学公式示例

行内公式：$E = mc^2$

块级公式：

$$
\int_0^\infty e^{-x^2} dx = \frac{\sqrt{\pi}}{2}
$$
