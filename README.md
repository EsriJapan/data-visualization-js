# data-visualization-js

ArcGIS API for JavaScript を用いてデータ ビジュアライゼーションの手法とそれを実現する機能について紹介していく「[JavaScript で始めるデータ ビジュアライゼーション](https://geonet.esri.com/docs/DOC-3492)」シリーズにおいて使用しているサンプル コード集です。

## サンプル

### 準備編

|[![](_images/01_1.png)](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=map)|[![](_images/01_2.png)](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=basic_add_data)|[![](_images/01_3.png)](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=basic_use_renderer)|
|:-:|:-:|:-:|
|[マップの表示](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=map)|[データの表示](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=basic_add_data)|[シンプル レンダラ](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=basic_use_renderer)|

### 個別値分類編

|[![](_images/02_1.png)](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=unique_value)|[![](_images/02_2.png)](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=unique_value_legend)|[![](_images/02_3.png)](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=unique_value_onthefly)|
|:-:|:-:|:-:|
|[個別値分類](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=unique_value)|[個別値分類（凡例付き）](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=unique_value_legend)|[カスタム カテゴリ](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=unique_value_onthefly)|

### 拡張オプション編

|[![](_images/03_1.png)](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=enhance_infotemplate)|[![](_images/03_2.png)](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=enhance_infotemplate_function)|[![](_images/03_3.png)](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=enhance_legend)|
|:-:|:-:|:-:|
|[属性情報の表示](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=enhance_infotemplate)|[属性情報の表示（関数）](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=enhance_infotemplate_function)|[凡例の表示](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=enhance_legend)|
|[![](_images/03_4.png)](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=enhance_click)|||
|[クリック イベント](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=enhance_click)|||

### 色表現編

|[![](_images/04_1.png)](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=color_simple)|[![](_images/04_2.png)](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=color_focus)|[![](_images/04_3.png)](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=color_stops)|
|:-:|:-:|:-:|
|[色表現](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=color_simple)|[カラーランプのフォーカス](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=color_focus)|[カラーランプの基点を作成](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=color_stops)|
|[![](_images/04_4.png)](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=color_classed)|||
|[数値分類](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=color_classed)|||

### 比例シンボル編

|[![](_images/05_1.png)](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=size_sample)|[![](_images/05_2.png)](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=size_unique_value)|[![](_images/05_3.png)](#)|
|:-:|:-:|:-:|
|[比例シンボル](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=size_sample)|[比例シンボルで個別値分類](http://apps.esrij.com/jsapi-blog/sandbox/sandbox.html?sample=size_unique_value)||

## 使用している製品・プロジェクト

* [ArcGIS API for JavaScript](https://developers.arcgis.com/javascript/)
* [ESRIジャパン オープンデータポータル](http://data.esrij.com/)
* [ArcGIS for Developers](https://developers.arcgis.com/en/)

**ArcGIS の開発キットを使用して開発を行う場合は ArcGIS Online 開発者アカウント（[ArcGIS for Developers](https://developers.arcgis.com/en/)）が必要です。開発者アカウントは無償で作成することができます。作成方法は[こちら](http://www.esrij.com/cgi-bin/wp/wp-content/uploads/documents/signup-esri-developers.pdf)**

## 動作環境

* Chrome
* Firefox
* Safari 3+
* Internet Explorer 7+

## リソース

* [GeoNet 開発者コミュニティ サイト](https://geonet.esri.com/groups/devcom-jp)
* [ArcGIS API for JavaScript（ESRIジャパン）](http://www.esrij.com/products/arcgis-api-for-javascript/)
* [ArcGIS API for JavaScript リファレンス](https://developers.arcgis.com/javascript/jsapi/)

## ライセンス
Copyright 2015 Esri Japan Corporation.

Apache License Version 2.0（「本ライセンス」）に基づいてライセンスされます。あなたがこのファイルを使用するためには、本ライセンスに従わなければなりません。本ライセンスのコピーは下記の場所から入手できます。

> http://www.apache.org/licenses/LICENSE-2.0

適用される法律または書面での同意によって命じられない限り、本ライセンスに基づいて頒布されるソフトウェアは、明示黙示を問わず、いかなる保証も条件もなしに「現状のまま」頒布されます。本ライセンスでの権利と制限を規定した文言については、本ライセンスを参照してください。

ライセンスのコピーは本リポジトリの[ライセンス ファイル](./LICENSE)で利用可能です。

[](EsriJapan Tags: <Data Visualization）>)
[](EsriJapan Language: <JavaScript>)
