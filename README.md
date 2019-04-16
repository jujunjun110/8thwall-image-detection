# 8thwall-image-detection-trial
8th-wall 11 beta から追加されたイメージ認識のテストプロジェクト

## 開発・デプロイ

- npm run dev → 開発サーバーの立ち上げ
- npm run test → ユニットテスト
- npm run dist → 本番反映用のビルド
- npm run deploy → Github Pagesへのデプロイ

## プロジェクト構成
```
├── dist/
│   ├── bundle.js
│   └── index.html
├── src/
│   ├── index.ts ← エントリーポイント
│   ├── js/
│   │   └── TypeScript コンポーネント(.ts)
│   ├── scss/
│   │   └── style.scss
│   └── shaders/
│       └── シェーダ（.ts, .vert, .frag)
├── test/
│   └── typescriptモジュールのテストコード
└── もろもろの設定ファイルたち
```
