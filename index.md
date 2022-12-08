---
title: AI-Image-Generate v1.0.0
language_tabs:
  - shell: Shell
  - http: HTTP
  - javascript: JavaScript
  - ruby: Ruby
  - python: Python
  - php: PHP
  - java: Java
  - go: Go
toc_footers: []
includes: []
search: true
code_clipboard: true
highlight_theme: darkula
headingLevel: 2
generator: "@tarslib/widdershins v4.0.11"


---

# AI-Image-Generate

> v1.0.0

# Default

## POST 数据请求接口

POST /get-image

> Body 请求参数

```yaml
prompt: A cute asian girl with long hair smiling and looking at me
n: "2"
size: 1024x1024

```

### 请求参数

| 名称         | 位置   | 类型   | 必选 | 说明           |
| ------------ | ------ | ------ | ---- | -------------- |
| Content-Type | header | string | 否   | none           |
| body         | body   | object | 否   | none           |
| » prompt     | body   | string | 是   | 生成图片的描述 |
| » n          | body   | string | 是   | 生成图片的数量 |
| » size       | body   | string | 是   | 图片的尺寸     |

> 返回示例

> 成功

```json
{
  "urlResponse": {
    "urlList": [
      "https://oaidalleapiprodscus.blob.core.windows.net/private/org-gDUd3bIEqkXFk0CeFYTAvwII/user-bB0NH80labaACQrnTVyyzcIF/img-brEOaOc3Y69PwEBxmBdpYIhN.png?st=2022-12-08T06%3A29%3A28Z&se=2022-12-08T08%3A29%3A28Z&sp=r&sv=2021-08-06&sr=b&rscd=inline&rsct=image/png&skoid=6aaadede-4fb3-4698-a8f6-684d7786b067&sktid=a48cca56-e6da-484e-a814-9c849652bcb3&skt=2022-12-08T03%3A31%3A26Z&ske=2022-12-09T03%3A31%3A26Z&sks=b&skv=2021-08-06&sig=dnNa6ga48u9Sa8Inx1TU2d4UXCdsxqpdLl7mM11RjIw%3D",
      "https://oaidalleapiprodscus.blob.core.windows.net/private/org-gDUd3bIEqkXFk0CeFYTAvwII/user-bB0NH80labaACQrnTVyyzcIF/img-JQCdRuElN5LPq5qxAHkOpsz9.png?st=2022-12-08T06%3A29%3A28Z&se=2022-12-08T08%3A29%3A28Z&sp=r&sv=2021-08-06&sr=b&rscd=inline&rsct=image/png&skoid=6aaadede-4fb3-4698-a8f6-684d7786b067&sktid=a48cca56-e6da-484e-a814-9c849652bcb3&skt=2022-12-08T03%3A31%3A26Z&ske=2022-12-09T03%3A31%3A26Z&sks=b&skv=2021-08-06&sig=eEDJhfg8%2Bn35/tL9QQX2pEY756dRAQ/XZKal9PHUTRM%3D"
    ]
  },
  "errorMessage": "OK"
}
```

### 返回结果

| 状态码 | 状态码含义                                              | 说明 | 数据模型 |
| ------ | ------------------------------------------------------- | ---- | -------- |
| 200    | [OK](https://tools.ietf.org/html/rfc7231#section-6.3.1) | 成功 | Inline   |

### 返回数据结构

# 数据模型

