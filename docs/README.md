# 職務経歴書

## 基本情報

|key|value|
|---|---|
|ハンドルネーム|ゆうすけ|
|生年月日|1992/09/14|
|出身|神戸|
|居住地|東京|
|最終学歴|工学研究科 電子情報工学専攻|
|職種|クラウドエンジニア|

---

## アカウント情報

- [Twitter:@anikinthos](https://twitter.com/anikinthos)
- [GitHub:akashikaikyouohasi](https://github.com/akashikaikyouohasi)
- [ブログ:Techまとめ](https://anikitech.com/)

---

## 保有スキル

- AWS上でのインフラ構築・運用監視
    - どんななサービスでも、キャッチアップして構築可能
- Linuxサーバ設計・構築・構築自動化
- IaCコード開発
    - AWS上にリソースを構築するためにTerraformコードを実装
    - SAMも利用してのLambda実装
- CI/CD
    - GitHub ActionsでTerraformやECSのCI/CD実装
- 運用自動化
    - StepFunctionsを利用して脆弱性対応自動化
- Pythonによるバッチ作成
    - LambdaやStepFunctionsで実装可能
- WEBサービスの運用
    - 高負荷時の原因究明や悪意のあるリクエストをWAFでブロック
    - 障害発生時のPlaybook作成やドキュメント、ダッシュボード作成と共有・フォロー
- 改善提案

---

## 技術スタック
### AWS
- 資格12個

### IaC
- Terraform
- CloudFormation
    - SAM(Serverless Application Model)
- Ansible

### OS
- Amazon Linux2, 2023
- 前職
    - Red Hat

### Middlewareなど
- Apache, nginx
- MySQL
- Postfix
- Datadog, Zabbix
- 前職のみ
    - DRBD
    - KVM, OpenStack
    - Elastic Stack(Elasticsearch、Beats、Logstash)
    - Grafana
    - PostgreSQL

### 言語
- Python
- ShellScript

---

## 保有資格

|資格|取得日|
|---|---|
|AWS PAS|2023年6月|
|AWS MLS|2023年6月|
|AWS ANS|2023年4月|
|AWS DAS|2023年3月|
|AWS DBS|2023年3月|
|AWS DOP|2023年2月|
|AWS DVA|2022年12月|
|AWS SCS|2022年11月|
|AWS SOA|2022年11月|
|AWS SAP|2022年5月|
|AWS SAA|2022年3月|
|AWS CLF|2021年12月|
|応用情報技術者|2017年6月|
|基本情報技術者|2014年6月|

---

## 職務経歴詳細

### 2社目（2022/08〜現在）
いわゆるSESをしている会社
#### 常駐先1(2022/08~現在)
介護SaaSなど複数のサービスを運営している上場企業にて、全社のインフラチームのクラウドエンジニアとして従事。主に手を動かす担当として、AWS上のサービスのインフラ構築や運用対応、監視アラート対応を担当。

- 経験した業務一覧
    - IaC
        - TerraformによるAWSのリソース構築
        - AnsibleによるEC2の設定自動化
    - AWS上での設計・実装
        - 開発メンバーからの要望実現
        - 基盤として提供しているメール送信システムのリニューアル
            - 1500万通/月程度送信している基盤
            - モニタリングやログ分析環境がなかったため必要なものを実装
            - 20サービス程度を移行中
        - バッチ処理をEC2からStepFunctions移行
        - EC2のECS移行
            - プロジェクトマネジメント
                - 責任者1名＋開発者2名＋インフラ1名（自分）
                - スケジュールの作成あkらタスク一覧の作成、移行統括
    - 運用
        - サービス
            - Datadog/Zabbixのアラート対応
                - Datadogのダッシュボード作成も実施
            - DNS管理
                - ずっと手動で変更していたので、TerraformでImportしてGitHub ActionsでCIを実装し、品質UP！
            - WAF管理
                - ブロック状況確認と対処
                - 悪意のある高頻度アクセスのブロック対応
        - AWS運用
            - AWSリソースのメンテナンス通知（RDS強制アプデやEC2のリブートなど）を対応
            - コスト削減
                - 無駄なECRイメージの削除や、Datadog起因のCloudWatch料金適正化で数割削減
                - 開発環境の夜間休日停止の提案と実装
                - 不要リソース削除(Cloudtrail二重取得など)
    - 運用効率化
        - 手動で実施したタスクの自動化
            - アラート発生時のAthena分析
            - EC2の脆弱性対応
        - Postmaster Toolsの最新状況把握をAPI経由でSlack通知
        - 長期的なメトリクスグラフがない外部サービスのメトリクス取り込みとダッシュボード化
    - 改善提案
        - AWSのメンテ通知確認がメールだったので、Backlog管理を提案
        - Gmailのスパム対策強化対応のための、迷惑メール率のSlack通知を提案
        - メールシステムのEOL対応の状況を詳細化し、必要な対応の明確化とプラン提案
        - EC2のcron処理のサーバレス化提案
        - 障害対応のPlaybookの作成とアラート通知文章への追記
        - 証明書更新の自動更新化
        - Route53管理のTerraform化
            - 手動変更でレビューが存在しなかった

### １社目（2017/04〜2022/07）
いわゆるSESをしている会社
#### 常駐先１(2017/06~2022/07)
大手ハードウェアベンダーにて、オンプレのインフラエンジニアとして従事。主に手を動かすメンバーとして、サーバの詳細設計やAnsibleによるサーバ構築効率化を担当。プロジェクトによっては、数人のメンバーのタスク管理も担当。

- 経験した業務一覧
    - オンプレサーバの詳細設計と構築
    - ミドルウェアの技術検証
        - 基本設計を指定したミドルウェアでどう実現するか
    - Ansibleによる効率的なサーバ構築
    - 2名〜5名人のメンバーのタスク管理
    - シェルスクリプトかPythonでバッチ作成
        - Python：pandasを利用した統計処理
    - 利用した技術スタック
        - 仮想化技術：KVM、OpenStack
        - OS：Red Hat Enterprise Linux
        - ミドルウェア
            - DB：MySQL、PostgreSQL
            - 監視：Grafana、Zabbix、
            - その他：Pacemaker、DRBD、ElasticSearch、


## 業務外活動
### 個人開発
- [aws_container_hands_on](https://github.com/akashikaikyouohasi/aws_container_hands_on)
    - [AWSコンテナ設計・構築[本格]入門](https://amzn.asia/d/ixSWxbF)を、コンソール画面ではなくTerraformでやってみたもの
    - 途中まで実施して、実際にECSを実務でやることになったので未完
- [spa-by-terraform](https://github.com/akashikaikyouohasi/spa-by-terraform)
    - SPA (Single Page Application) をAWS上にTerraformでイミュータブルに構築
    - SPAはログインしてプロフィールを表示できるだけ
    - Reactで作成し、Auth0を利用してTwitter経由でログインできる
    - インフラはAWSで構築。基本的にはTerraformを流すだけでできる（Auth0はTerraformの範囲外）


### 執筆活動など
- [個人ブログ:Techまとめ](https://anikitech.com/)
    - 1500PV/月程度
    - 2023年2月現在：13記事
- [CloudTech](https://kws-cloud-tech.com/)：AWS試験問題作成プロジェクト
    - 2022年12月〜2022年2月
    - SOAの問題追加プロジェクトにて、SOAチームリーダー兼レビュアー兼作成
    - 参考：[謝辞ページ](https://kws-cloud-tech.com/aws-certificate-thanks)
- [AWS認定資格 ソリューションアーキテクトアソシエイトの教科書: 合格へ導く虎の巻](https://www.amazon.co.jp/AWS%E8%AA%8D%E5%AE%9A%E8%B3%87%E6%A0%BC-%E3%82%BD%E3%83%AA%E3%83%A5%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3%E3%82%A2%E3%83%BC%E3%82%AD%E3%83%86%E3%82%AF%E3%83%88%E3%82%A2%E3%82%BD%E3%82%B7%E3%82%A8%E3%82%A4%E3%83%88%E3%81%AE%E6%95%99%E7%A7%91%E6%9B%B8-%E5%90%88%E6%A0%BC%E3%81%B8%E5%B0%8E%E3%81%8F%E8%99%8E%E3%81%AE%E5%B7%BB-CloudTech%E6%9B%B8%E7%B1%8D%E4%BD%9C%E6%88%90%E5%A7%94%E5%93%A1%E4%BC%9A-ebook/dp/B0BCPNZ9GJ/ref=sr_1_10?keywords=aws+%E3%82%BD%E3%83%AA%E3%83%A5%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3%E3%82%A2%E3%83%BC%E3%82%AD%E3%83%86%E3%82%AF%E3%83%88+%E3%82%A2%E3%82%BD%E3%82%B7%E3%82%A8%E3%82%A4%E3%83%88&qid=1676799670&sprefix=AWS+%E3%82%BD%E3%83%AA%E3%83%A5%2Caps%2C171&sr=8-10)
    - 2022年8月31日出版
    - サンプル問題にて、問題と解説と図の作成の一部を担当
- [AWSで実践するEC2の脆弱性対応: 脆弱性ってなんですか？でも大丈夫！EC2の脆弱性対応を知識0からEC2脆弱性をハンズオン対応](https://www.amazon.co.jp/dp/B0CH71BKVV?ref=cm_sw_r_cp_ud_dp_YQ9MSZW71AHCWXSRP3VN_1&ref_=cm_sw_r_cp_ud_dp_YQ9MSZW71AHCWXSRP3VN_1&social_share=cm_sw_r_cp_ud_dp_YQ9MSZW71AHCWXSRP3VN_1)
    - 2023年9月2日出版
    - 執筆（著者名はペンネームです）

---

## 意欲・興味
- SREではなくてもいいでのですが、やりたいことに一番近いのはSREと考えています
- やりたいことと、そこに至った思考の流れ
    - 働いている会社を成長させるには、システム・サービスを継続的に改善し、競合に勝つ必要がある
    - そのためには、サービス・システム開発速度と信頼性の向上と、人員が開発へより注力できることが必要では？
    - 自分はインフラをメインとしているので、直接的に開発することはない
    - なら、開発しやすい環境を整えることや、何度もやっていることの自動化、差別化ポイントではないが必要な機能のプラットフォーム化、デプロイしやすいようにするなどしていきたい
    - これってSREとかPlatform Engineeringが近いかな？

### 今後の目標
- SREとPlatform Engineeringのプラクティスを理解し、実践していく
- より影響の大きいシステムに携わる

---

