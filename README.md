# linear-garaph# 
📈 数学探検ツール

スライダーを動かすだけで、関数のグラフが変わる学習ツールです。
成長期の子供が関数の「かたち」を直感的に理解できるよう作りました。

## ページ一覧

| ファイル | 内容 |
|---|---|
| `index.html` | 指数関数 y = a · e^(b·x) |
| `linear.html` | 一次関数 y = ax + b |

## 使い方

スライダーを動かすと式とグラフがリアルタイムで変わります。
「おためしパターン」ボタンで代表的な形をワンタップで確認できます。

## GitHub Pages への公開

```bash
# 1. リポジトリを作成してファイルを配置
git init
git add index.html linear.html
git commit -m "first commit"
git push origin main

# 2. GitHub の Settings → Pages → Source を main に設定
# 数分後に公開されます
```

公開後の URL 例：
- `https://ユーザー名.github.io/リポジトリ名/` （指数関数）
- `https://ユーザー名.github.io/リポジトリ名/linear.html` （一次関数）

## 動作環境

外部ライブラリは CDN から読み込むだけで、ビルド不要・サーバー不要です。
モダンブラウザ（Chrome / Safari / Firefox / Edge）で動作します。
