---
name: API作成依頼
about: 新規プロジェクト等で必要になるAPIの作成を依頼する
title: "[依頼] [エンドポイント名]"
labels: "api作成依頼"
---

# 概要

- プロジェクト : 

## queryParameter

- limit :
- offset :
- order :

> API項目名 + "_" + ソート方法(asc|desc)。','区切りで複数指定
> 例) order=genreKbn_desc,genreKbnID<br>

## requestBody

  ```json
{
  "ID": 1234
}
```

## response

```json
{
  "ID": 1234
}
```
