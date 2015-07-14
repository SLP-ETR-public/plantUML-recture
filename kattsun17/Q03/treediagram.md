クラス図についての分析
(特に疑問に思った部分には行末に"?"と記載)

# class 入金部

## 属性

- 入金額
  - 入金を得た額の総額を持つ

## 処理

- 入金処理を行う()
  - 入力されたコインや札がどの金額か調べ、入金額に加算する


# class おつり出口

## 属性

- お釣り
  - お釣りの金額

## 処理

- 返却する
  - お釣りの金額から、その額のコインを排出する

# class レジスタ

## 属性

- 選択された商品の価格
  - 選択された商品の価格をおもつ

- 各飲料の売上げデータ
  - 各商品が何個売れたか

## 処理

- 入金金額と商品価格を照らし合わせる()
  - 入金部が持つ入金額と、商品の価格を照らし合わせる

- お釣りを割り出す()
  - お釣り出口が持つお釣りと、購入された商品の価格を照らし合わせる

# clas 商品口

## 処理

- 商品を排出する
  - 商品を排出する


# class 商品保持部

## 属性

- 商品の価格
  - 各商品の価格

- 商品の適正な温度
  - 各商品の適正な温度

- 在庫数
  - 商品の在庫数

# class 商品管理部

## 属性

- 温度
  - 保管庫の現在の温度

# 処理

- 商品をひやす()
  - 商品保持部の商品の適正な温度から、商品を冷やす

- 商品を温める()
  - 商品をひやすと同様


} 


ボタンがない
表示