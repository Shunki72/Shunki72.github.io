# Google OAuth / GitHub Pages template

## ファイル構成

- `index.html` : 今後の個人アプリをまとめるトップページ
- `styles.css` : 共通CSS
- `apps/<app>/index.html` : アプリ専用ホームページ
- `apps/<app>/privacy.html` : アプリ専用プライバシーポリシー
- `.nojekyll` : GitHub Pagesで静的ファイルをそのまま配信するための空ファイル

## OAuthに設定するURLの例

GitHubユーザー名が `example-user` で、ユーザーサイトリポジトリ
`example-user.github.io` を使う場合:

- Homepage URL:
  `https://example-user.github.io/apps/calendar/`
- Privacy Policy URL:
  `https://example-user.github.io/apps/calendar/privacy.html`

独自ドメイン `apps.example.com` を設定した場合:

- Homepage URL:
  `https://apps.example.com/apps/calendar/`
- Privacy Policy URL:
  `https://apps.example.com/apps/calendar/privacy.html`
