# AkiBoard

今夜空いてるお店をリアルタイムで探せる飲食店向けプラットフォームです。

## ページ構成

| ファイル | 説明 |
|---|---|
| `index.html` | お客さん向け空き一覧（メイン） |
| `store.html` | 店舗管理画面（空き公開・登録） |
| `lp.html` | 店舗オーナー向けLP・料金案内 |

## 使い方

### お客さん
`index.html` を開くと今夜空いてるお店の一覧が表示されます。

### 店舗オーナー
1. `store.html` を開く
2. 「店舗登録」タブで店舗情報を登録
3. 「空き公開」タブで今夜の空き情報を公開

## 技術スタック（現在）
- 静的HTML / CSS / JavaScript
- localStorage でデータ管理（デモ版）

## 今後の予定
- Next.js + Supabase + Vercel への移行
- Supabase Realtime でリアルタイム更新
- Instagram Graph API でストーリーズ自動投稿
- Stripe Billing で課金
