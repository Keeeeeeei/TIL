## Cookieのやり取りについて
Webサーバーに接続したブラウザに対して、コンテンツと一緒にブラウザに保存して欲しい内容をCookieとして送信する。

## メッセージヘッダーの利用
Cookieの送信にはメッセージヘッダーが利用されます。WebサーバーはHTTPレスポンスに”Set-cookie”ヘッダーを含める事で送信でき、WebブラウザはHTTPリクエストに”cookie”ヘッダーを含める事で送信できる。

## 注意
Cookieはブラウザの認識にも利用するため、盗まれると他人のなりすましなども可能。セキュリティの観点から、ショッピングサイトなどには使用される。