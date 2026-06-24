# 株式会社インフォダイレクト サービス紹介LP

美容業界に特化した電話代行サービス「株式会社インフォダイレクト」のランディングページ（LP）です。

## 公開URL

GitHub Pagesで公開しています。

🔗 https://tanitanistudio.github.io/ikigai-lp/

## ページ内容

- 美容業界専門・36年250社の代行実績の紹介
- 「オペレーター対応」「AI」「AI×オペレーター」の3プラン紹介
- 初回導入限定の完全従量課金プランの案内
- 導入実績・お客様の声
- 資料請求・無料相談フォーム

## ファイル構成

```
.
├── index.html              # LPメインページ
├── contact_confirm.html    # 無料相談フォームの確認画面
├── document_confirm.html   # 資料請求フォームの確認画面
├── thanks.html             # フォーム送信完了画面
├── style.css               # スタイルシート
└── img/                    # 画像・アイコン類
```

## 技術構成

- HTML / CSS（フレームワーク不使用の静的サイト）
- フォントは Google Fonts（Noto Serif JP、Noto Sans JP ほか）を使用
- 資料請求・無料相談フォームは Google Apps Script（GAS）と連携して送信処理を行っています

## ローカルでの確認方法

静的ファイルのみで構成されているため、`index.html` をブラウザで直接開くか、簡易サーバーを立てて確認できます。

```bash
python3 -m http.server 8000
```

ブラウザで `http://localhost:8000` にアクセスしてください。
