# PaaS の時代到来

heroku で普及したRails PaaSですが、2013年1月時点で海外・国内に渡り数々のサービスが提供されています。
見渡してみたいので列挙します。

業務システム構築の視点なので、海外ベンダーより国内ベンダーを重視します。

## 各種PaaS 概観
----
### 国内
----

#### IIJ MOGOK http://mogok.jp/

　日本のインターネットの雄 iij がもともとまつもとさんが所属するNaCL
（まえださんやRuby界の神々を抱える）と組んでクラウドサービスGIOメニューにRails PaaSのMOGOKを追加。β中。
　国内サーバなので速いし、iijの信頼感もあり業務システムクラウドの本命。

 サービス状況
 2012/10 オープンβ

 参考紹介記事
　http://itpro.nikkeibp.co.jp/article/NEWS/20121030/433675/

----
#### ペパポ sqale https://sqale.jp/feature
　Webサービスサーバ分野では大手のペパポが提供するsqaleもすでに有償サービス開始。

 サービス状況
 2012/8 本番

 参考紹介記事
ペパボ、月額940円のRuby対応PaaS「Sqale」スタート
http://ascii.jp/elem/000/000/719/719776/

----
#### ニフティクラウド C4SA http://c4sa.nifty.com/
　ニフティもPaaS正式提供。

 サービス状況
 2012/7/31 本番

 参考紹介記事
  http://el.jibun.atmarkit.co.jp/rails/2012/07/rubyphppythonpa-36ca.html

----
#### fluxflex http://www.fluxflex.com/

  草分け的 2010年時点で始まっていた。今はサンフランシスコに行ってしまった。

 サービス状況
 2010/11 本番

 参考紹介記事

　http://jp.techcrunch.com/archives/jp-20101025-fluxflex-can-use-ec2-by-several-clicks/

----
#### NTT Com BizホスティングCloud n PaaS http://www.ntt.com/cloudn/data/paas.html

　Cloud Foundry利用。企業向け開始中。個人向けは2013/3予定。

 サービス状況
 2012/12 企業向け本番
 2013/03 個人向け本番

 参考紹介記事
　http://news.livedoor.com/article/detail/7200720/

----
#### TIS eXcale https://www.excale.net/

　 β 12月に試しましたが、BootStrapがうまく動かず

 サービス状況
 2012/10 β

 参考紹介記事
　http://www.tis.co.jp/news/2012/20121015_1.html

----
### 海外系
----

#### Heroku http://www.heroku.com/

　SalesForceのSaaS先駆者のグループの中で、Rubyの父 まつもとさん、中田さん（Rubyのパッチ貢献王）、
笹田さん（Ruby1.9以降のVM YARV開発者）も抱え込んで最大の勢力。ベースはEC2なのでレイテンシや事故の難点も。

 サービス状況
 2010/ SalesForece傘下に
 2011/12 heroku ja meetup開始

 参考紹介記事
　http://builder.japan.zdnet.com/virtualization/sp_heroku2012/35018326/

----
#### Amazon Elastic Beanstalk http://aws.amazon.com/jp/elasticbeanstalk/

　アマゾンもPaaS提供 β。

 サービス状況
 2012/12 Rubyサポートを発表

 参考紹介記事
http://www.publickey1.jp/blog/12/amazonrubyelastic_banstalkjavaphppythonnetruby.html

----
#### デル Project Fast PaaS
　http://www.dell.com/Learn/us/en/555/cloud-computing/dell-cloud-computing-foundry

　プレビュー中。Croud Foundry利用。

 サービス状況
 2012/12 プレビュー版公開

 参考紹介記事
　http://www.publickey1.jp/blog/12/paasproject_fast_paascloud_foundry.html

----
#### Engine yard http://www.engineyard.co.jp/

　老舗。日本語のサービスも開始している。

 サービス状況
 2012/9 日本法人設立
 2012/11 オラクル出資発表

 参考紹介記事
　http://www.publickey1.jp/blog/12/engine_yardoracle_cloudrubyphpnodejspaas.html

----
#### Redhat OpenShift https://openshift.redhat.com/

　Node.jsに力が入っていそう。

 サービス状況
 2012/8 β提供中
 2012/年内 有償化予定

 参考紹介記事
http://itpro.nikkeibp.co.jp/article/Active/20120801/413456/

----
#### Cloud Foundry http://www.cloudfoundry.com/

　Cloud Foundryはクラウドサービスを実現するオープンソースプロジェクト。
　VMWare社が自社サービスでも提供している。

 サービス状況
 2013/1現在 各社のサービスで利用されている

 参考紹介記事
  http://www.atmarkit.co.jp/fnetwork/rensai/cloudfoundry01/01.html

----
#### DotCloud http://www.dotcloud.com/

 参考紹介記事
　http://www.publickey1.jp/blog/11/paasdotcloud.html

　宮川達彦氏が、その後DotCloudから Cookpadに移動されたので、その後はどうなのでしょうね。

----
### 〔番外〕
----
#### Duostack http://www.duostack.com/
 参考紹介記事
　http://tech.a-listers.jp/2011/05/03/duostack-open-beta/
　今はどうなってる？
----


