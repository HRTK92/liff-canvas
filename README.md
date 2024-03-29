# liff-canvas
[![Run on repl.it](https://repl.it/badge/github/HRTK92/liff-canvas)](https://repl.it/github/HRTK92/liff-canvas}&ref=button)

LINE上で絵を書くことができそのまま送信することができます。
ペンの色や太さ、背景の色など設定することができ気軽に図など送ることができます。

[こちら](https://engineering.linecorp.com/ja/blog/liff-our-latest-product-for-third-party-developers/)の記事を参考に作成しました

https://user-images.githubusercontent.com/70054655/181139667-8d6b02db-2d8f-4801-a712-c8a149f31bd3.mp4

## 起動方法

### インストール

```sh
pip install -r requirements.txt
```

### 起動

```sh
python app.py
```

## LIFFアプリとして追加

追加の仕方は以下のサイトから確認してください
[LINE Developers](https://developers.line.biz/ja/docs/liff/registering-liff-apps/#registering-liff-app)

注意
Scopeで```chat_message.write```が必要になります

## 使い方

### 設定について

ペンの太さや色、バックカラーを選べます。

![イメージ](./static/Screenshot_20210807-094808.png)
