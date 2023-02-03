# 2022gsc_WataruYoshida
吉田航の2022年度ゼミ論用レポジトリ
# 【2022年度ゼミ論】PLATEAU LOD1 建物データをOSMにインポートする際の事前準備【OSMのみの妥当性検証におけるエラー・警告の事例収集】
地球社会共生学部　地球社会共生学科　3年A組188番

学籍番号：1A120189　氏名：吉田航

指導教員：古橋　大地教授

©Furuhashi Laboratory/Wataru Yoshida, CC BY 4.0

## Abstract

本研究では、国土交通省主導の日本全国の3D都市モデルの整備・活用・オープンデータ化を目指すプロジェクト[PLATEAU](https://www.mlit.go.jp/plateau/)のLOD1の建物データを誰でも編集可能な地図[OpenStreetMap](https://www.openstreetmap.org/#map=15/35.7449/139.4576) (以下OSM)にインポートする作業を行う際の事前準備として、

## Introduction
10月の2022 10月 [UN/EC Open Source Software for SDG (OSS4SDG) Hakcathon](https://github.com/furuhashilab/README/issues/33#issuecomment-1281762516)にて青山学院大学　地球社会共生学部の古橋　大地教授及びYouthMappersAGUが中心となって取り組んだ[PLATEAU](https://www.mlit.go.jp/plateau/)で公開されている東村山市のLOD1建物データをOSM(https://www.openstreetmap.org/#map=15/35.7449/139.4576) にインポートする際の作業の内の一つである【妥当性検証】の際に「表示されたエラー・警告がOSMによる問題なのか、PLATEAUによる問題なのかが判別できない」という問題が発生した。私たちはこの問題の対処法として「インポート作業の事前準備としてOSMのみの妥当性検証を実施し、修正作業を行う」という考えに至った。この一連の作業をマニュアル化・実施することによりインポートする際の妥当性検証で表示されたエラー・警告はPLATEAUのデータによるものであると判別がつき、インポート作業の効率化が見込める。本研究では、[JA:MLIT PLATEAU/imports list](https://wiki.openstreetmap.org/wiki/JA:MLIT_PLATEAU/imports_list)を参考として次なるインポート地域を埼玉県新座市とし、マニュアル作成に向けた【エラー・警告の事例収集】を[Tasking Manager](https://tasks.teachosm.org/projects/1499/tasks/?page=1)とJOSMを用いて行った。

## Methods

## Results


## Discussion


## Conclusion


## 謝辞
本研究を進めるにあたり地球社会共生学部の古橋大地教授をはじめ多くの方々より多大な助言を賜りました。厚く感謝を申し上げます

## 先行事例

https://github.com/yuuhayashi/citygml-osm/issues/96#issue-1429854543

https://qiita.com/nyampire/items/1c10afdd36750c87154d 


## 新規性
* PLATEAUからOpenStreetMapに3D建物データをインポートし、建物データを更新する点


## メリット
* PLATEAUという国土交通省が主導しているプロジェクトということもあり、かなり正確なデータをインポートすることができる

* OpenStreetMap上の3D建物データを最新版に更新することができる


## 参考文献
