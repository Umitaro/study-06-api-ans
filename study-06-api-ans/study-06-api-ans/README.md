課題６の解説
====

# 解説動画
https://youtu.be/CyUbfUmOGNs


以下は課題の内容

# 1
VSCODEにREST Clientプラグインをインストールして楽天の商品APIを実行して結果が返ってくることを確認してみましょう。  
REST Clientの使い方:https://protoout.studio/posts/visual-studio-code-api-rest-client
商品検索APIの仕様:https://webservice.rakuten.co.jp/api/ichibaitemsearch/

# 2
以下の仕様を参考にして、任意のキーワードでAPIを検索した時の
商品名と価格の一覧を取得してみましょう
https://webservice.rakuten.co.jp/api/ichibaitemsearch/

# 3 
以下のAPIを使って、任意の商品の最安値と最高値を取得してみましょう  
https://webservice.rakuten.co.jp/api/productsearch/

# 4
以下のAPIを使って、任意のジャンルのランキング一覧を取得し、CSV出力してみましょう
https://webservice.rakuten.co.jp/api/ichibaitemranking/

# 5
pytestをinstallして、単体テストを実施してみましょう<BR>
- インストール<BR>
`pip install pytest`<BR>
- テスト実行<BR>
`python -m pytest <pyファイルのpath>::<テストしたい関数名> -s`  <BR>
