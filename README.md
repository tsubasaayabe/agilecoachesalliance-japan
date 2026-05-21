# Agile Coaches Alliance Japan

アジャイルコーチたちのコミュニティサイト

## 概要

Agile Coaches Alliance Japanは、アジャイル開発における実践的なコーチングと組織変革を推進する専門家たちのコミュニティです。

## サイト構成

- **私たちについて**: 組織のミッションと価値観
- **メンバー紹介**: 7人のコーチプロフィール
- **お問い合わせ**: 連絡先情報

## ファイル構成

```
.
├── index.html          # メインサイト（1ページ）
├── README.md          # このファイル
└── .gitignore         # Git設定ファイル
```

## ローカル実行

HTMLファイルをブラウザで直接開くか、ローカルサーバーで実行してください。

```bash
# Python 3.x でサーバーを起動する場合
python -m http.server 8000

# Python 2.x の場合
python -m SimpleHTTPServer 8000

# Node.js (http-server) を使用する場合
npx http-server
```

ブラウザで `http://localhost:8000` にアクセスしてください。

## GitHub Pages デプロイ

このサイトはGitHub Pagesで公開されています。

### デプロイ手順

1. このリポジトリを GitHub にプッシュします
2. リポジトリの Settings → Pages に移動
3. Source を「Deploy from a branch」に設定
4. Branch を「main」「/root」に設定
5. Save をクリック

数分後、サイトが `https://<username>.github.io/agilecoachesalliance-japan` で公開されます。

## 技術仕様

- **言語**: HTML5 + CSS3
- **フレームワーク**: なし（バニラHTML）
- **レスポンシブ対応**: ✓ モバイル、タブレット、デスクトップ対応
- **ブラウザサポート**: 全ての現代的ブラウザに対応

## デザイン

- **カラースキーム**: グラデーション（紫系）を使用した洗練されたデザイン
- **レイアウト**: グリッドベースのレスポンシブレイアウト
- **アニメーション**: ホバーエフェクトでインタラクティブな体験を実現

## 今後の拡張予定

- メンバーの詳細プロフィールページ
- ブログセクション
- お問い合わせフォーム（バックエンド連携）
- 多言語対応（英語など）

## ライセンス

MIT License

## 連絡先

info@agilecoaches-alliance-japan.example
