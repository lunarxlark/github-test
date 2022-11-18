---
name: API作成依頼
about: 新規プロジェクト等で必要になるAPIの作成を依頼する
title: "[依頼] [エンドポイント名]"
---

# 概要

- どのプロジェクトで必要か :  `giraffe`  (phoenixやbug, etc...)
- どの機能で使用するか : `マスタ > hoge > fuga > 一覧 > 更新`

## queryParameter

- limit : `1`
- offset : `2`
- order : 記法は下記参照

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
