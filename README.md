# 草を生やすブログ フロント

公開：Cloudflare Pages
プロキシサーバー：Cloudflare Workers (Hono) 

1. ブラウザの投稿フォームから記事を送信
2. Cloudflare Workers (Hono) がリクエストを受け取り GitHub Actions を起動
3. GitHub Actions がマークダウンファイルを追加してコミット
4. Cloudflare Pages が自動でリビルド・デプロイ


## 更新について
**⚠️ ソースコードを直接触る時は必ずgit pullしてから。**

【記事の更新方法】
- Cloudflare Pagesの追加ページから
- 本プロジェクトのcontent/postsに直接mdファイルを追加

