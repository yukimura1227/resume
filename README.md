# Curriculum-Vitae-tmp
This is template of curriculum vitae. Please use this template when need your curriculum vitae.
=======
# 職務経歴書

## 基本情報

|key|value|
|---|-----|
|Name|高村宏幸|
|生年|1985年|
|Blog|[挫折から始まるプログラム開発奮闘記(最近更新していない)](http://yukimura1227.blog.fc2.com/)|
|Qiita|[yukimura1227](https://qiita.com/yukimura1227)|
|Twitter|[@takamura1227](https://twitter.com/takamura1227)|
|coconala|[yukimura1227](https://profile.coconala.com/users/19294)|

## スキル
### プログラミング言語
- Ruby
- Java
- Javascript
- C,C++ (大学生時代に使っていた)

### サーバサイドフレームワーク
- Ruby on Rails
- Struts1系
- Spring
- MyBatis

### フロントエンドフレームワークなど
- Vue.js(少々)
- Webpack
- React（17以降）

### CSSフレームワークなど
- ui-kit(少々)
- bootstrap(少々)

### テストフレームワークなど
- jUnit(4系)
- Rspec
- jest(少々)

### 開発手法
- ウォーターフォール(2008/06〜2016/02)
- スクラム(2016/03〜)

### Cloud
- AWS
  - EC2
  - S3
  - RDS
  - SQS
  - ecs
  - ecr
  - codebuild
  - codepipeline

### Infrastructure as Code
- terraform
- Ansible
  - 未導入の状態から既に構築手順がわからないインフラを業務の傍らで長期的にコード化した
- Chef(少々)
- Puppet(少々)
- Vagrant
- Docker

### Platform as a Service
- Heroku

### Linux
- 業務で滞りなく扱える程度
- 基本的なトラブルシュートはできる程度

### CIツール
- CircleCI
  - 業務で使っている。
- TravisCI
  - 嗜む程度(テスト回して、electronアプリのパッケージングをしたりする程度)
  - [参考：.travis.yml](https://github.com/yukimura1227/reveal_lightning/blob/development/.travis.yml)
- Appveyor(少々)
- Jenkins(少々)

### 監視ツール
- mackerel(少々)
- zabbix(少々)

他にもあるので、TODO

### Deployツール
- capistrano

## チームリード・チームビルド
### 開発部全体のリーダーとして、チームを牽引
「エンジニアのLTV(Life Time Value)の総和を最大化する」というテーマを打ち出して、改善活動を行う(仕掛り中)
- LT(Life Time)を伸ばす(長期的にサービスに貢献してもらう)
  - 広義の意味でのDX(Developer Experience)の向上活動(研究会を開く、リファクタリング時間を確保する、プロトタイプの作成時間を確保するなど)
  - メンバーとの1on1を通じて、課題の吸い上げや、課題解決のサポート
- V(Value)を伸ばす(貢献度を上げる、生産性を上げる)
  - 生産性の向上(テンプレ化、部品化の促進。自動化の提案、低生産性部分の見える化と改善)
  - ビジネス理解を深めていくための、体制づくり
  - 未経験エンジニアに対するOJTパートナー制度の導入と、未経験採用時の教育・育成指針の立案(OJTをされる側とも一緒に内容を話し合ってたたき台づくり)
- エンジニアを増やす(これを増やさないと総和が増えないため)
  - エンジニア採用専属部隊づくり
  - 多面的な採用活動
    - 即戦力層
    - ポテンシャル(未経験層) (教育制度の立案とセット)
    - 学生バイトからの社員化 (教育制度の立案とセット)
    - 採用広報のためのネタづくり

### コードレビュー時のコメントにラベルをつけようぜ運動
以下のような、ラベルをつけることを推奨。(![badge](https://img.shields.io/badge/review-NOTE-green.svg) のようなbadge画像は使わずに、[NOTE] のようなテキストベースでも、全く問題ありません。)

| バッヂ | ラベル | 用途 | 備考 |
| ---- | ---- | ---- | ---- |
| ![badge](https://img.shields.io/badge/review-NOTE-information.svg) | [NOTE] | ただのメモ書き。 | `![badge](https://img.shields.io/badge/review-NOTE-information.svg)` |
| ![badge](https://img.shields.io/badge/review-ADVICE-information.svg) | [ADVICE] | 参考意見や、知っていると便利な知識などの、アドバイス。 | `![badge](https://img.shields.io/badge/review-ADVICE-information.svg)` |
| ![badge](https://img.shields.io/badge/review-QUESTION-blue.svg) | [QUESTION] | 質問や疑問 | `![badge](https://img.shields.io/badge/review-QUESTION-blue.svg)` |
| ![badge](https://img.shields.io/badge/review-NITS-blue.svg) | [NITS] | 本質的ではない、すごい細かい指摘。 | `![badge](https://img.shields.io/badge/review-NITS-blue.svg)` |
| ![badge](https://img.shields.io/badge/review-REQUEST-important.svg) | [REQUEST] | 調査・確認してほしい、ついでにこっちも直してほしいといった依頼事項。 | `![badge](https://img.shields.io/badge/review-REQUEST-important.svg)` |
| ![badge](https://img.shields.io/badge/review-IMO-important.svg) | [IMO] | In My Opinion.(私ならこうするけど、どうかしら？) | `![badge](https://img.shields.io/badge/review-IMO-important.svg)` |
| ![badge](https://img.shields.io/badge/review-MUST-critical.svg) | [MUST] | バグっていたり、危険な実装。(ラベル自体が強いので、なるべく本文は、柔らかい表現を心がけましょう。) | `![badge](https://img.shields.io/badge/review-MUST-critical.svg)` |

### ブランチの命名規則を統一しようぜ運動
以下の命名規則を推奨。

| 名前 | 用途 | 備考 |
| ---- | ---- | ---- |
| feat/ | 機能追加・機能修正 | ※test,refactor,miscなコミットを含んで良い。 |
| fix/ | バグfix | ※test,refactor,miscなコミットを含んで良い。 |
| test/ | テスト追加・テスト修正 | ※テストだけ追加・修正する場合 |
| refact/ | リファクタ | ※リファクタだけ実施する場合 |
| misc/ | その他(プログラム以外のみ) | ※ README.mdの修正だけするなど。 |

### コミットメッセージの書き方を揃えようぜ運動
以下のコミットメッセージformatを推奨。

```
label[must] (namespace[optional]): title[must]

description[optional]

footer[optional]
```

1. *label* の種類

* feat: 機能追加・修正
* fix: バグfix
* refact: リファクタ
* test: テスト修正・テスト追加のみの場合(featと同じタイミングでコミットする場合はfeatを使う)
* docs: ドキュメント修正(コメント含む)
* style: レイアウト微調整など
* perf: パフォーマンス関連の修正
* chore: その他

2. *namespace* is put in parenthesis after label and is optional.
3. *title* is a brief summary of changes.
4. *description* is **optional**, new-line separated from title and is in present tense.
5. *footer* is **optional**, new-line separated from *description* and contains "fixes" / "references" attribution to github issues.

Example:

```
fix(Page): fix page.pizza method

This patch fixes page.pizza so that it works with iframes.

Fixes #123, Fixes #234

```

参考元：  
- [angular.jsのガイドライン](https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#-git-commit-guidelines)
- [puppeteerのガイドライン](https://github.com/GoogleChrome/puppeteer/blob/master/CONTRIBUTING.md#commit-messages)

## 言語
- 日本語
  - ネイティブ
- 英語
  - ドキュメントを、調べながら読むことに抵抗はない

## 実績ベースでのtopic
- 未導入の状態からAnsibleの導入とチームへの啓蒙活動
- rails4 -> rails5 のバージョンアップをリードした
- ruby2.4 -> ruby2.5移行
  - yumでのgcc,g++のバージョンの食い違いでamazon linuxでは非常に面倒
  - Amazon Linux2に全移行した(Ansibleを完全化した)
- paizaでの各種ゲームの開発
  - [恋するハッカソン ~君色に染まるアイドル~](https://paiza.jp/poh/hatsukoi)
  - [もし次の常駐先が女子エンジニアばっかりだったら](https://paiza.jp/moshijo)
  - [ロジックサマナー 閃光の召喚プログラマ](https://paiza.jp/logic_summoner)
  - [一攫千金プログラミング~ボットdeジャックポット~](https://paiza.jp/paizajack)
- ローカル開発環境のDocker導入
  - MySQL,ElasticMQ,MongoDB,mailcatcher,redisの構築をHomebrew管理 -> docker-compose.yml管理化
- スナップショットテストの導入
  - jestを使って、日時で昨日と今日の画像の差分をチェックする仕組みを導入
  - 月一で棚卸しをして、差分をどうするか決める運用を主導
  - ※2019/07/11時点 大きな成果は挙げられていないので、改善策を模索中
- testのcoverage向上運動
  - codecovを使って、coverageの視覚化を実施
  - KPIに掲げられるような、働きかけ
  - 事業運営とのバランスを見ながら、長期的なcoverage向上運動の実施
- Python2で書かれていたレガシーコードのRuby移行
- お試しで、ログ視覚化サーバの構築・導入(実績づくり)
  - Elasticsearch
  - Kibana
  - Fluentd
- Ask Me Anything企画
  - 社長とみんなが遠いよねといった課題解決のため
  - エンジニアと非エンジニアが遠いよねといった課題解決のため
  - slackで一定時間、なんでも聞いてねみたいな企画を実現しました。
- 1on1のポイントの明文化
  - 目的が明確ではない1on1をやっていたので、明確化した
- 開発チームのroleとスキルマップの策定(仕掛中)
- 開発チームの年表を作成し、運用を啓蒙した(仕掛り中)
- 社内のMTGをHangoutを使って、ライブ中継する文化を作った
- 社内の図書購入と貸借管理のアプリを作って効率化した
- サーバ証明書の期限切れでアクセスができなくなるような事案でも前向きに、証明書の更新の自動化を組み込んで再発防止に努めた
- 技術的負債返済の文化を全社的に浸透させた
- 技術的負債という言葉が独り歩きしていて、課題感を感じたので是正した
  - 理想と現実のギャップ -> これは、技術的負債とは呼ばないようにしよう(∵ 一生埋まらないので、疲弊するので)
  - 技術的負債 = チームとして当たり前にしておきたい状態と現実のギャップ(当たり前なので、返済のやり方が明確にわかっている)
  - 技術的闇 = 放置すると絶対にヤバいが、どうしたらいいかわからないようなもの
- 未経験エンジニア採用からの社内教育について、未経験エンジニアも巻き込んでアウトラインを作った(仕掛かり中)

## 強み
- エンジニア外も含めた、オールラウンダー
  - インフラ・サーバサイド・フロントエンドの開発・運用・保守が、まぁまぁできる
  - エンジニアの立場、相手の立場になって多角的に物事を判断できる
    - エンジニアサイドに偏らず、双方の言い分を咀嚼して話を整理して合意に至れることが多い
      - TODO: 具体例
  - 1on1などを通じて、チームの状況確認、メンタリング、コーチングを実施できる
  - エンジニアの採用を行う
  - エンジニアの評価を行う
- 直面している課題に応じて柔軟に振る舞いを変えられる
  - 必要だと判断した場合は、やりたくないことも一定時間(半年とか1年とか)、職務変更で対応できる
    - ただし、苦手領域においてパフォーマンスが出せるとは言っていない
    - 例えば、人事っぽい動きが必要だと思ったらそういう動きする(採用基準策定、評価制度の画策)
- 無意識的に人間観察をし続けている
  - 相手の気持ちを想像する能力は高い(たぶん)
- 大変な時でも、前向きでいられるし、常に気づきを得て、成長の糧にしている(と思う)
- 長期的に効果を発揮するルールや文化をコツコツ浸透させることができる
  - テストを書いていく文化
  - コミットログの推奨の付け方
  - ブウランチの推奨の切り方
  - DeveloperExperience自体と、それを上げるために何ができるか？を全エンジニアで考えていく文化
  
## 弱み
- ある程度、サクセスストーリが見えないと、動きが、少し鈍くなる
- 採用まではDRYに切り捨てるが、採用後は、あまりDRYには徹することが苦手
- イノベーションを起こすような、0-1は、思いついたことがない

## やったことはないが興味があるもの
- Google Cloud Platform
- フロント系(強くはないので)
  - React
  - Angular

<!-- TODO
## 職務経歴

### yyyy/mm - 現在 : 会社名

職務: Webアプリケーションエンジニア（例）

#### 職務内容の名前（レストラン検索とか）

- 職務内容の詳細を箇条書きでかく

### yyyy/mm - yyyy/mm: （前職の企業名。あれば）

職務: サーバーサイドエンジニア

#### 職務内容の名前（レストラン検索とか）

- 職務内容の詳細を箇条書きでかく

## 課外活動

### 社外プロジェクト
* [運営に携わっているコミュニティ](そのコミュニティのconnpassやカンファレンスページのリンクとか)
* [副業で携わっているサービス](そのサービスのランディングページのリンクとか)

### 過去の登壇資料
* [Speaker Deck](Speaker Deckの自分の資料のページとか)

### 受賞歴
* [イベント名と受賞した賞](イベントのランディングページのリンクや、結果がわかる記事など)
-->

### 執筆歴
* 僕の考え方がわかるような記事たち
  * [[新人ITエンジニア伝えたい]自身の価値を高め続けていくための7つのポイント](https://qiita.com/yukimura1227/items/482f1cacf304148166b2)
  * [10年目のエンジニアが新人に教えたい、この仕事で重要な14のこと](https://paiza.hatenablog.com/entry/2018/09/05/10%E5%B9%B4%E7%9B%AE%E3%81%AE%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%8B%E3%82%A2%E3%81%8C%E6%96%B0%E4%BA%BA%E3%81%AB%E6%95%99%E3%81%88%E3%81%9F%E3%81%84%E3%80%81%E3%81%93%E3%81%AE%E4%BB%95%E4%BA%8B%E3%81%A7)
  * [よいエンジニアチームを作るためにリーダーがやっている6つのこと](https://paiza.hatenablog.com/entry/2019/05/27/%E3%82%88%E3%81%84%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%8B%E3%82%A2%E3%83%81%E3%83%BC%E3%83%A0%E3%82%92%E4%BD%9C%E3%82%8B%E3%81%9F%E3%82%81%E3%81%AB%E3%83%AA%E3%83%BC%E3%83%80%E3%83%BC%E3%81%8C%E3%82%84)
  * [SIer村を出て自社サービスに行った、若いエンジニアの末路](https://paiza.hatenablog.com/entry/2018/01/29/SIer%E6%9D%91%E3%82%92%E5%87%BA%E3%81%A6%E3%81%84%E3%81%A3%E3%81%9F%E3%80%81%E8%8B%A5%E3%81%84%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%8B%E3%82%A2%E3%81%AE%E6%9C%AB%E8%B7%AF)
  * [なぜプロジェクトは炎上するのか？炎上しやすい4つの傾向と、炎上を防ぐ3つの対策](https://paiza.hatenablog.com/entry/2016/07/28/%E7%82%8E%E4%B8%8A%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AB%E8%87%AA%E5%88%86%E3%81%8B%E3%82%89%E9%A3%9B%E3%81%B3%E8%BE%BC%E3%82%93%E3%81%A7%E3%81%84%E3%81%A3%E3%81%9F%E3%82%A8)

### 登壇履歴
2019/07時点では、特にないですけど強いて言うなら以下
 - [コーディングスキルチェックから就活→実務へ](https://gi-no.github.io/public_documents/20180217_student_event/)

### 成果物
#### reveal_lightning 
frontエンドの勉強目的で作った、markdownでプレゼン資料が作れるreveal.jsの、動作環境つきエディタ。  
[yukimura1227/reveal_lightning](https://github.com/yukimura1227/reveal_lightning)  
[reveal_lightningについて](https://yukimura1227.github.io/try_github_pages/about_reveal_rightning/)

#### librarian
amazonのURLを伝えると、会社の本として購入してくれる福利厚生があったので、その発注と貸借を管理するためのWebアプリ  
[librarian](https://github.com/yukimura1227/librarian)

#### mameshiba-slack-bot
社内のルールをゆるく周知して、ルール自体の改善を促すためのbot  
[yukimura1227/mameshiba-slack-bot](https://github.com/yukimura1227/mameshiba-slack-bot)

#### jobcan_do_it
jobcanで出勤・退勤をするためのコマンドラインツール
[yukimura1227/jobcan_do_it](https://www.npmjs.com/package/jobcan_do_it)

### 資格
- 基本情報処理 2006.04取得
- ソフトウェア開発技術者 2008.04取得
- CIW Web Foundations Associate 2008.06取得
- SEA-J 2008.07取得
- XMLマスター：ベーシック 2008.09取得
- SJC-P 2009.03取得
- セキュリティスペシャリスト 2013.10取得
- データベーススペシャリスト 2015.04取得
