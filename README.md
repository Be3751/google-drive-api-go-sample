# google-drive-api-go-sample
## 概要
[Google Drive API Go クイックスタート](https://developers.google.com/drive/api/quickstart/go?hl=ja)に従って動作確認したサンプルコード。   
アクセストークンを取得するために必要な`credentials.json`は、Google Cloud コンソールの[API とサービス] > [認証情報] > [OAuth 2.0 クライアント ID]から取得する必要がある。  

## 補足
リダイレクト先にあるクエリパラメータ`code`がAPIを利用する上で必要な点に注意。（ドキュメント内に記載の「[ブラウザからコードをコピーして](https://developers.google.com/drive/api/quickstart/go?hl=ja#:~:text=%E3%82%AF%E3%83%AA%E3%83%83%E3%82%AF%E3%81%97%E3%81%BE%E3%81%99%E3%80%82-,%E3%83%96%E3%83%A9%E3%82%A6%E3%82%B6%E3%81%8B%E3%82%89%E3%82%B3%E3%83%BC%E3%83%89%E3%82%92%E3%82%B3%E3%83%94%E3%83%BC%E3%81%97%E3%81%A6,-%E3%80%81%E3%82%B3%E3%83%9E%E3%83%B3%E3%83%89%E3%83%A9%E3%82%A4%E3%83%B3%20%E3%83%97%E3%83%AD%E3%83%B3%E3%83%97%E3%83%88)」
だと少し分かりにくいため）
