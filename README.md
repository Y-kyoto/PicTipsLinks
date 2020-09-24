[![Netlify Status](https://api.netlify.com/api/v1/badges/f7d6a758-677b-42f9-8178-cd5a2a80c0bb/deploy-status)](https://app.netlify.com/sites/gallant-bohr-faa6a7/deploys)

https://gallant-bohr-faa6a7.netlify.app/

# ページ追記の仕方
## twitter埋め込み
1. [https://publish.twitter.com/](https://publish.twitter.com/)か[GET statuses/oembed](https://developer.twitter.com/en/docs/twitter-api/v1/tweets/post-and-engage/api-reference/get-statuses-oembed) 経由で埋め込み用のHTMLを取得する。
2. 埋め込み用のHTMLの `<blockquote>〜</blockquote>` を`.md`　ファイルに追記する。

## youtube
youtubeから発行されるHTMLを使用する。
使用した動画は[この再生リスト](https://www.youtube.com/playlist?list=PLfaxCAFIhb8BzUAjq95298WlSUgBO0_ck)に追加する。

## pixiv
```
<a href="https://embed.pixiv.net/decorate.php?illust_id={イラスト固有ID}&amp;mode=sns-automator" title="{イラストタイトル}">
<img alt="{イラストタイトル}" class="http-image" src="https://embed.pixiv.net/decorate.php?illust_id={イラスト固有ID}&amp;mode=sns-automator"></a>
```
と指定するることで埋め込むことができる。ただし公式でのブログパーツの提供は終了している。１ページ目が表紙でない場合は埋め込みではなくテキストでのリンクを優先する。

## その他のサイト
[ブログカード風の紹介リンクタグ作成](https://matsmoto.jp/tool/link-001/)を使用する。
