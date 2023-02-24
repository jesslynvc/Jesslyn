
Kintone UI Component - v0 maintenance stop & migration to v1
https://bozuman.cybozu.com/k/36902/show#record=548

---
title: "kintone UI Component v0 メンテナンス終了のお知らせ"
description: "kintone UI Component v0 メンテナンス終了についてお知らせします。"
date: "2023-02-16T00:00:00Z"
hasToc: false
category: "サイト情報"
type: "single"
layout: "news"
---

「cybozu developer network」をご利用いただき、ありがとうございます。  
kintone UI Component v0 は、2023 年 12 月 31 日にメンテナンスを終了します。  
kintone UI Component v0 を使ってカスタマイズを実施している場合は、継続的な開発が行われている kintone UI Component v1 への移行を推奨します。

### kintone UI Component v0 のメンテナンス終了について {#details}

<!-- textlint-disable no-doubled-joshi -->

[kintone UI Component v0](https://kintone-labs.github.io/kintone-ui-component/latest/)（以下、v0）は、2021 年 3 月の kintone UI Component v1（以下、v1）のリリースに伴い、新規機能の開発が終了し、メンテンスモードになっていました。  
v1 の開発に注力するため、2023 年 12 月 31 日をもって、セキュリティアップデートを含めた開発を終了します。  
GitHub からのダウンロードおよび npm でのインストールにて、引き続き v0 を利用できますが、脆弱性の対応やブラウザーの互換性に対する修正は行われなくなります。  
また kintone のアップデートの影響を受けて、kintone が動作しなくなる可能性やスタイル崩れが発生する可能性があります。

<!-- textlint-enable -->

#### v0 を利用しているかを確認する方法 {#confirm-v0}

v0 を利用している場合には、開発者コンソールで以下を実行すると `true` が返ります。

<!-- eslint-disable -->
```js
!!kintoneUIComponent;
```

### kintone UI Component v1 への移行 {#migration}

v0 を使ってカスタマイズを実施している場合には、 安定的に利用できる [kintone UI Component v1](/kintone/sdk/library/kintone-ui-component-v1/) への移行を推奨しています。

v1 では、アクセシビリティ対応やモバイルのコンポーネント追加など、v0 にはない機能が含まれています。  
継続的な開発を実施しているため、kintone の機能追加や [kintone フロントエンド基盤刷新](https://kintone.cybozu.co.jp/update/main/2022-08.html) に対する対応も行っています。  
また、v1 では、テクニカルサポート（API 窓口）を通じて、仕様の確認やトラブルを問い合わせできます。  
[サポートへのお問い合わせ方法](https://jp.cybozu.help/k/ja/id/040274.html) を確認の上、お問い合わせください。  
[GitHub Issue](https://github.com/kintone-labs/kintone-ui-component/issues) でも、質問や機能リクエストを受け付けています。

v1 に移行する場合には、カスタマイズのソースコードの修正が必要です。  
書き方の違いは、[A commentary on the difference between v0 and v1](https://kintone-ui-component.netlify.app/docs/ja/guides/comparison-v0-v1) を参照してください。

### v0 と v1 の機能差異 {#feature-difference}

v1 には、v0 の機能のうち提供していない機能もあります。  
詳しくはそれぞれのドキュメントサイトを確認してください。

* [kintone UI Component v1](https://kintone-ui-component.netlify.app/ja/)
* [kintone UI Component v0](https://kintone-labs.github.io/kintone-ui-component/latest/)

### 関連記事 {#reference}

* [kintone UI Component v1](/kintone/sdk/library/kintone-ui-component-v1/)
* [kintone UI Component v0を使って動的ドロップダウンを作成しよう！](https://developer.cybozu.io/hc/ja/articles/360014149732)