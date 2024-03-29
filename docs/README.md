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
- Linuxサーバ設計・構築・構築自動化
- IaCコード開発
    - AWS上にリソースを構築するために、Terraformコードの開発経験があります
- 運用自動化
    - AWSではAutomationを利用して脆弱性対応自動化を行なったりしていました
- Pythonによるバッチ作成
    - pandasで統計データの集計用のバッチを作成したことがあります

---

## 技術スタック
### AWS
- 資格8個

### IaC
- Terraform
- CloudFormation
- Ansible

### OS
- Amazon Linux2
- Red Hat

### Middleware
- Apache
- MySQL,PostgreSQL
- DRBD
- KVM, OpenStack
- Elastic Stack(Elasticsearch、Beats、Logstash)
- Grafana
- Zabbix

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
プロジェクト詳細は後ほど書きたい

### 2社目（2022/08〜現在）
いわゆるSESをしている会社
#### 常駐先1(2022/08~現在)
介護SaaSなど複数のサービスを運営している上場企業にて、全社のSREチームのエンジニアとして従事。主に手を動かす担当として、AWS上のサービスのインフラ構築や運用対応、監視アラート対応を担当。Ansibleの経験とTerraformの個人学習おかげで、IaCに関しては効率的に実施できていました。
また、EC2の脆弱性対応の自動化やメンテナンス通知の集約の提案など、運用効率化を実施していました。

- 経験した業務一覧
    - IaC
        - TerraformによるAWSのリソース構築
        - AnsibleによるEC2の設定自動化
    - AWS上での設計・実装
        - 開発メンバーからの要望実現
    - 運用
        - サービス
            - Zabbixなどからのアラート対応
            - DNS管理
        - AWS運用
            - AWSリソースのメンテナンス通知（RDS強制アプデやEC2のリブート）を元に対応案の提案と実施
    - 運用効率化
        - 手動で実施したタスクの自動化

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
    - 2023年2月時点で、5-3章まで完了
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

---

## 意欲・興味
- SREではなくてもいいでのですが、やりたいことに一番近いのはSREと考えています
- やりたいことと、そこに至った思考の流れ
    - 働いている会社を成長させるには、システム・サービスを継続的に改善し、競合に勝つ必要がある
    - そのためには、サービス・システム開発速度の向上と、人員が開発へより注力できることが必要では？
    - 自分はインフラをメインとしているので、直接的に開発することはない
    - なら、開発しやすい環境を整えることや、何度もやっていることの自動化、デプロイしやすいようにするなどしていきたい
    - これってSREが近いかな？

### 今後の目標
- AWSの資格をすべて取得
- CI/CDについて理解を深める
- SREのプラクティスを理解し、少しでいいから実践していく

---

