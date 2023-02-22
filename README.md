# resume

0xwata の職務経歴書
職務経歴およびスキルなどをまとめたページです。
[Github Pages](https://0xwata.github.io/resume/) でもご覧いただけます。

- [どんなエンジニアか、どんなエンジニアでありたいか](#どんなエンジニアかどんなエンジニアでありたいか)
- [どんなところで働きたいか](#どんなところで働きたいか)
- [基本情報](#基本情報)
- [SNS](#SNS)
- [職務経歴](#職務経歴)
- [その他活動プロジェクト](#その他参加プロジェクト)
- [資格](#資格)
- [学歴/研究](#学歴/研究)
- [趣味・好きなもの](#趣味・好きなもの)

# どんなエンジニアかどんなエンジニアでありたいか

- 事業を起こす（0→1→10)を再現性を以て何回も繰り返せる存在になりたい。またその経験を積んでいきたい。
  - 必要であればエンジニアのお仕事以外もやりまっせというスタンスですが、適材適所という言葉もあるので、自分がキャパオーバーになるくらいなら適度なタイミングで適切な人に頼る姿勢も大事だと思ってます。
- 色々やってきましたが、今は Android エンジニアです。
  - やっぱりユーザーが触る UI を構築して出来上がっていく時のワクワク感
  - 学生の頃は、研究やインターンの関係で、Python, Ruby でよく書いていました。あまり言語に対するこだわりは強くないですが、kotlin は好きです。
  - バックエンドに興味がないわけではないです。機会があればチャレンジしてみたいです。
- 元々新卒入社した会社では、データサイエンティストとして採用してもらっており、データ分析や数字を見て改善することは好きです。（現職ではアプリの品質を監視するチームのリーダーとしてクラッシュフリー率・再生成功率の改善や、監視体制の改善などをしてたりしました）
- 大学院では、テキストマイニング・自然言語処理に関する研究もやっていたので、そちらの方面のスキル・知識も多少あります。最近流行ってる生成系のモデルに関してはたまにキャッチアップしている程度です。
- 「リスクを取らない」リスクに対して焦りがあり、早め早めに経験を積んでおきたいマインドを持っています。

# どんなところで働きたいか
* プロダクト
*   自社で開発してるサービスがあり、その開発に携われる
      * 自分達発信で変えていける
      * 成長を感じ取れる
  * そのサービスに対して自分が共感できる。
* フェイズ
  * 今よりも小規模な会社である。
* 年収
  * 今より上がる場所。
* その他
  * 技術への投資に理解があること


# 基本情報

| 項目     | 内容               |
| -------- | ------------------ |
| 氏名     | 高嶺 航            |
| 生年月日 | 1994 年 4 月 13 日 |
| 性別     | 男                 |

# SNS

| 項目     | 内容                               |
| -------- | ---------------------------------- |
| Twitter  | <https://twitter.com/___wata___>   |
| Facebook | https://www.facebook.com/0xwata/   |
| Wantedly | https://www.wantedly.com/id/oxwata |

# 職務経歴

## 合同会社 DMM.com

【期間】2020/04 - 現在
【事業内容】各種インターネットサービス業
【当時の社員数】約 3000 人

### 所属・役割

- 2020/8 - 現在：動画配信事業部 デバイスアプリチーム Android エンジニア

主なプロジェクト
|プロジェクト|期間|言語|利用技術|役割|メンバー|内容|
|--|--|--|--|--|--|--|
|動画視聴アプリの ExoPlayer 導入|2020/7-2021/7|Kotlin, Java|--|エンジニア|1 人|主にアナリティクスイベントやプレイヤーログへのパラメータ送信とプレイヤー設定の UI 実装を行いました。|
|アプリ品質改善のための指標導入・計測・運用|2021/10 - 2021/7|--|--|リーダー <br> 要件定義|3 人|SLI チームとして既存指標に加えて再生開始までの時間・レンダリング時間・DL 成功率という新しい指標を３つ導入、計測、運用まで行なった。途中から SLI チームのリーダーとして、Redash × Slack, Firebase × Slack の連携により自動で品質指標が達成されてるかを通知される仕組みを構築。また週毎及び月毎に SLO の一つである再生成功率が確認できるダッシュボードを作成して、アプリの品質を監視できる体制を整えた|
|アプリアップデート通知の運用最適化|2020/7-2021/7|Kotlin|--|エンジニア|1 人|--|
|課金サンプルアプリの開発（主に決済機能の実装）|2020/7-2021/7|Kotlin|Google Play Billing Library|エンジニア| 5 人|新規事業のビジネスモデルを検討する上でアプリ内課金の知見が社内にあまりなかったので、アプリ内課金を検証するサンプルアプリを開発した。Google Play Billing Library を使用し、主に課金回りの実装を担当。新規事業のアプリ内課金の仕様を検討する上で、資金決済法や課金回りの AppleStore, Google Play Store のガイドラインを読み込んだ。|
|ボイラープレート自動作成コードによる開発効率改善|2020/7-2021/7|Ruby|--|エンジニア|1 人|KMM で開発しているプロジェクトで iOS, TV, Android の開発者が実装する共通部分のボイラープレートを生成するコードを作成し、Mobile の開発グループが活用できる形で共有した。|
|DMM TV の開発|2021/7 - 現在|Kotlin, JavaScript, Swift|CicleCi, DataDog, Jetpack Compose, KMM, Graphql,|エンジニア|20 人（Android, iOS) <br> 10 人（Android）|Jetpack Compose を用いた作品詳細画面 (Web だと[この画面](https://tv.dmm.com/vod/?season=5zuv9s3rax7kd90ex8rhuwt0o)の UI 実装及び画面に必要なデータを Apollo 経由で取得する部分の実装を担当。全ての画面の中で一番仕様が複雑で、GraphQL のスキーマにおいて各フィールドがどういう条件で画面上のどのパーツに対応するかのマッピング作業を Web も含めたクライアントサイドのエンジニアの方々と一緒に主体的に進めていきました。また実装途中で作品詳細画面の API レスポンス速度が遅い&&データを取得するクエリの Complexity が高いことが課題となっていたため、解決に向けて主体的に取り組みました。クエリの分割(FirstView に必要なデータとそれ以外で分割)&& オーバーフェッチの削除し、Complexity を 1500 → 750(レスポンス速度も半分以上になった。)にすることを達成しました。自分が担当した作品詳細周りの課題解決にあたっては、開発しているアプリが動画配信アプリなので、動画再生に至るまでの体験を快適にすることを軸に改善を進めることが重要だと思っており、日々心がけて業務にあたっています。|

その他の取り組み

- 新卒技術研修のサービス発案・ソリューション企画のメンター
- テストに関する輪読会の実施

# その他活動プロジェクト

- [Worldwide StRhyme](https://minori-products.wixsite.com/minori/%E8%A4%87%E8%A3%BD-%E7%A7%81%E3%81%B8%E3%81%86%E3%81%A4%E3%82%8B-1)
  - 役割：韻フレーズの収集
  - その他展示情報
    - [11/18-22 multi-lingua-body](https://www.instagram.com/p/ClGlfC4y-kZ/)
- 週末プロトタイピング
  - https://hometeeee.studio.site/
# スキル・経験

[スキルリスト](/skills.md)

# 資格など

| Certification      |
| ------------------ |
| 基本情報処理技術者 |

# 学歴/研究

## 2018/04 - 2020/03 東京大学工学系研究科 技術経営戦略学専攻 和泉研究室

- 修士論文
  - 経済レポートを対象とした因果関係に着目するクエリ志向型複数文書要約
- 課外活動
  - デジタルアート「[韻を踏む](https://www.wacoal.jp/studyhall/gallery/event/article143564)」の制作
    - 役割: 押韻フレーズの収集・言語処理
    - 受賞: SICF20 ワコールスタディホール京都奨励賞
  - [Signate J リーグ観客動員数予測コンペ 上位 10%入賞](https://signate.jp/competitions/27)
    - データ分析のコンペに出場し、時系列回帰のタスクにおいて、Ridge 回帰を用いて上位 10%入賞を果たしました。
  - キャリアパス可視化ツールの開発
    - 詳細: Rails + MySQL + Cytoscape.js で開発
    - URL: https://github.com/0xwata/careercompass
  - [100BANCH Filter Bubble Busters](https://100banch.com/magazine/26213/) での活動

## 2014/04 - 2018/03 東北大学工学部 機械知能航空工学科

- 在籍研究室
  - 吉田研究室
    - 卒業研究: 月面探査機の走行時の障害物認識
- 受賞
  - [グローバル萩海外留学奨励賞](https://www.bureau.tohoku.ac.jp/kikin/japanese/office/news_pop/news_201609_01.html)
- 課外活動
  - 人力飛行機部
    - 在籍期間: 2014 - 2015
    - 成績: [第 38 回鳥人間コンテスト選手権大会人力プロペラ機ディスタンス部門 優勝](https://www.tohoku.ac.jp/japanese/2015/09/news20150915-01.html)

# 趣味・好きなもの

- サウナ
- アイドル（櫻坂・乃木坂・エビ中）
- サッカー
- お香
- レコード
- アニメ
- マンガ
- 二郎（仙台二郎しか知りません）
