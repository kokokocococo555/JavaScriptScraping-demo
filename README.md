# JavaScriptScraping-demo
JavaScriptでコンテンツが生成されるサイトのスクレイピングのデモ【Selenium+PhantomJS】

## 流れ

1. SeleniumとPhantomJSでJavaScriptを用いるサイト（今回は「[note](https://note.mu/)」）からHTMLを抽出
2. 抽出したHTMLをBeautifulSoup4でパースし、必要な情報を抽出
3. MongoDBにデータを保存
4. csv形式でデータを保存
5. RSS形式でデータを保存

## 参考
コードは主に以下を参考にさせていただきました。

- [『Pythonクローリング＆スクレイピング―データ収集・解析のための実践開発ガイド―』技術評論社](https://gihyo.jp/book/2017/978-4-7741-8367-1)
