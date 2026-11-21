<p align="center">
  <img src="docs/icons/computer.svg" width="72" alt="Computer">
</p>

<h1 align="center">情報処理・AI学習</h1>

<p align="center">
  応用情報技術者試験・G検定対策を、流れるカードで楽しく反復学習。
</p>

<p align="center">
  <strong>2,000項目</strong> ・ <strong>重複なし</strong> ・ <strong>1.0倍で約22分／周</strong>
</p>

![情報処理・AI学習のメイン画面](docs/images/matrix-learning-overview.png)

## <img src="docs/icons/book-open.svg" width="24" alt="Book Open"> このアプリについて

応用情報技術者試験やG検定に関連する情報処理・AIの学習項目を、マトリックス風のカードとして表示するブラウザアプリです。全2,000項目を一度ずつ表示してから再シャッフルするため、同じ周回内では内容が重複しません。

## <img src="docs/icons/bot.svg" width="24" alt="Bot"> 学習分野

| アイコン | 分野 | 項目数 |
|:---:|---|---:|
| <img src="docs/icons/bot.svg" width="22" alt="Bot"> | AI・G検定 | 700 |
| <img src="docs/icons/computer.svg" width="22" alt="Computer"> | 応用情報・基礎技術 | 600 |
| <img src="docs/icons/shield-check.svg" width="22" alt="Shield Check"> | セキュリティ | 300 |
| <img src="docs/icons/database.svg" width="22" alt="Database"> | ネットワーク・DB・クラウド | 250 |
| <img src="docs/icons/scale.svg" width="22" alt="Scale"> | 法務・倫理・マネジメント | 150 |
|  | **合計** | **2,000** |

## <img src="docs/icons/gauge.svg" width="24" alt="Gauge"> 主な機能

| アイコン | 機能 | 内容 |
|:---:|---|---|
| <img src="docs/icons/shuffle.svg" width="22" alt="Shuffle"> | 重複防止 | 2,000項目を出し切ってから再シャッフル |
| <img src="docs/icons/gauge.svg" width="22" alt="Gauge"> | 速度調整 | 0.25倍〜3.0倍。1周の予想時間も自動表示 |
| <img src="docs/icons/pause.svg" width="22" alt="Pause"> | 一時停止 | 読みたいカードを現在位置で停止・再開 |
| <img src="docs/icons/palette.svg" width="22" alt="Palette"> | 配色変更 | 用語・意味・枠・背景・カード内部を個別設定 |
| <img src="docs/icons/maximize.svg" width="22" alt="Maximize"> | 全画面表示 | 学習画面をクリックして全画面へ切り替え |

## <img src="docs/icons/computer.svg" width="24" alt="Computer"> クイックスタート

1. このリポジトリをダウンロードまたはcloneします。
2. `index.html`をブラウザで開きます。
3. 右上で速度を調整し、学習を始めます。

外部ライブラリのインストールやビルド作業は不要です。`index.html`と`knowledge.js`は同じフォルダに置いてください。

## <img src="docs/icons/book-open.svg" width="24" alt="Book Open"> ドキュメント

- 画像付きの詳しい使い方：[操作ガイド](USER_GUIDE.md)
- Lucideアイコンのライセンス：[Third-Party Notices](THIRD_PARTY_NOTICES.md)

## ファイル構成

```text
matrix-learning/
├─ index.html                 # 画面・描画・操作パネル
├─ knowledge.js              # 分野別の学習データ
├─ README.md                 # プロジェクト紹介
├─ USER_GUIDE.md             # 画像付き操作ガイド
└─ docs/
   ├─ images/                # 操作画面
   └─ icons/                 # Lucide SVGアイコン
```
