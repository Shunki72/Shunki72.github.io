# Google OAuth / GitHub Pages template

## 置換する文字列

公開前に、リポジトリ内を一括検索して次を置換してください。

- `YOUR_NAME` : 公開してよい名前または開発者名
- `YOUR_EMAIL` : OAuthサポート用として公開してよいメールアドレス
- `YOUR_CALENDAR_APP_NAME` : Google Auth Platformの「アプリ名」と揃えることを推奨

## ファイル構成

- `index.html` : 今後の個人アプリをまとめるトップページ
- `styles.css` : 共通CSS
- `apps/calendar/index.html` : Calendarアプリ専用ホームページ
- `apps/calendar/privacy.html` : Calendarアプリ専用プライバシーポリシー
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

## 注意

このテンプレートのプライバシーポリシーは、
「Pythonアプリがローカルで動作し、Google Calendarデータを外部サーバーへ恒久保存しない」
ケースを想定しています。

実際のコードが外部サーバーへの送信、クラウド保存、ログ保存、第三者サービスとの連携などを
行う場合は、必ず実態に合わせてプライバシーポリシーを修正してください。
