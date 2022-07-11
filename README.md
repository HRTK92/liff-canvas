# liff-canvas
[![Run on repl.it](https://repl.it/badge/github/HRTK92/liff-canvas)](https://repl.it/github/HRTK92/liff-canvas}&ref=button)

LINE上で絵を書くことができそのまま送信することができます。
ペンの色や太さ、背景の色など設定することができ気軽に図など送ることができます。

![](./static/IntroductoryVideo.mp4)

## 起動方法

### インストール

```sh
pip install -r requirements.txt
```

### 起動

```sh
python main.py
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
