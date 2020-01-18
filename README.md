# データサイエンティスト　テスト問題

## 概要

サービスAを対象に、アプリのログインを促すために6/3~6/9の1週間、一部のユーザーに対してメッセージをプッシュする施策を行いました。

メッセージタイプには"A"と"B"の2種類があり、それぞれ受け取るユーザー群が異なります。メッセージのプッシュ回数については1回のユーザー群と2回のユーザー群があります。メッセージプッシュの効果として翌週(6/10 ~ 6/16)のログイン回数が増えたことが認められれば、メッセージのプッシュを全ユーザーに展開しようと計画しています。

施策効果を比較するためにプッシュメッセージを配信してないユーザー群を対照群としたとき、今回の施策効果について分析を行ってください。

## 解析対象ファイル

* user_login.csv: サービスAのユーザーごとのログイン時刻
    * user_id: ユーザーID
    * timestamp: ログイン時刻のタイムスタンプ

* experimental_design.csv: プッシュメッセージの配信状況
    * user_id: ユーザーID
    * push_cnt: プッシュ回数 (0回, 1回, 2回)
    * msg_type: メッセージタイプ(None, A, B)
    
## 提出物

* 解析レポート:サービス企画担当(データ解析の非専門家)への提出を想定して、日本語で作成してください。
* ソースコード: データ解析で用いられたツールのソースコード。
* ケースの解決については、HTMLのノートブックを参照してください。

For the resolution of this case, please see the HTML Notebook in the repository.
<a id="raw-url" href="https://github.com/fkaminishi/push_notification_test/blob/master/DS_test%20vKaminishi.nb.html" download>Download FILE</a>
