expressとpassportモジュールでGoogleアカウントログイン機能

# 起動方法

[Google API Consoleから「Client ID」と「Secret Key」を取得する](http://ablogcms.io/hands-on/snsLogin.html)

承認済みのリダイレクトURLを `http://localhost:8000/return` とする
承認済みのJavaScript生成元は空欄で大丈夫

```bash
$ CLIENT_ID=__Google_CLIENT_ID__ CLIENT_SECRET=__Google_CLIENT_SECRET__ node server.js
```

ブラウザでに [http://localhost:8000/](http://localhost:8000/) にアクセスする



