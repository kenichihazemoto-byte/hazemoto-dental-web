# ハゼモト建設 歯科見積アプリ（Web・公開版）

サーバ計算版の薄いクライアント。**原価・単価・マスタは持たず**、Supabase Edge Function で計算します。
（GitHub Pages で公開可能：このリポジトリには原価は含まれません）

- 概算計算：Supabase Edge Function `estimate`
- 図面自動読取：Supabase Edge Function `analyze-drawing`（要 `ANTHROPIC_API_KEY` シークレット）
- 社内限定URL・認証弱め（弱トークン）。堅くする場合は Supabase Auth を追加。
