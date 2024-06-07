# 全ゲノム解析ウェブサイト一覧

細菌における全ゲノム解析を行う際に、有用なサイトを紹介します。

## 標準作業手順書（SOP）
### PulseNet (CDC) 
https://www.aphl.org/programs/food_safety/Pages/PulseNet-International-SOPs.aspx

CDC PulseNetのSOP。DNA抽出からデータクオリティチェックまで。

### 結核研究所 結核菌ゲノム解読の標準作業手順書(2023年7月)
https://jata.or.jp/data.php

日本語での培養からシークエンスデータを得るまでSOP。対象菌は結核菌ですが、DNA抽出以降の手法は基本的には多くの細菌で共通です。

<br>
<br>

## 様々な解析が行えるサイト
### Galaxy
https://usegalaxy.org/

多種多様なゲノム解析が可能です。

アセンブリには、SPAdesがよく使われます。一般的なペアエンドデータの場合、「Paired-end: individual datasets」を選択します）


### CGE server 
(http://www.genomicepidemiology.org/services/)

デンマーク工科大学（Technical University of Denmark）が運営するサーバー。各種型別や系統解析が行えます。

<br>

## 系統樹作製
最尤法 (maximum likelihood method)を用いるのが主流です。

<br>

#### IQ-TREE Web Server
http://iqtree.cibiv.univie.ac.at/

最尤法でのモデル選択、系統解析が自動で行えます。

<br>

## アノテーション（塩基配列への遺伝子情報の付与）
#### DFAST
https://dfast.ddbj.nig.ac.jp/

DDBJが運営しています。プログラムのダウンロードも、ウェブサーバーでの解析も可能。

#### Bakta
https://bakta.computational.bio/

ProkkaやDFASTより新しいアノテーションプログラム。プログラムのダウンロードも、ウェブサーバーでの解析も可能。

<br>


## 解析結果の可視化ソフト
#### MEGA
https://www.megasoftware.net/

系統樹作製等の解析もできます。


#### FigTree
http://tree.bio.ed.ac.uk/software/figtree/

系統樹の表示ソフト。

#### iToL
https://itol.embl.de/

系統樹に菌株情報（メタデータ）等を加えることができます（多くの機能は有料版）。

#### PopART
https://popart.maths.otago.ac.nz/

Minimum Spanning Network解析等が可能です。必要なNexusファイルは、MEGA等で作製することが可能です。

#### GrapeTree
https://github.com/achtman-lab/GrapeTree

オンラインでminimum spanning treeの作製ができます。

#### GView Server
https://server.gview.ca/

全遺伝子を対象としたBLAST(BLAST atlas)等が可能です。

#### Phandango
http://jameshadfield.github.io/phandango/#/

系統樹に菌株情報（メタデータ）をつけて表示することが可能です。


<br>

## 薬剤耐性遺伝子検索
#### ResFinder
http://genepi.food.dtu.dk/resfinder

菌種、データ形式（FASTA or FASTQ）を選んで実行します。

<br>

***

## 菌種別解析サイト

### 大腸菌
#### 血清型別（SerotypeFinder）
https://cge.food.dtu.dk/services/SerotypeFinder/

大腸菌の血清型別。OX等の一部の新規血清型には対応していません。

#### 病原性遺伝子検出 (VirulenceFinder 2.0)
https://cge.food.dtu.dk/services/VirulenceFinder/

大腸菌の他、Listeria, Stapylococcus aureus, Enterococcusでも可能です。

<br>

## データベース
### EnteroBase
https://enterobase.warwick.ac.uk/

Salmonella, Escherichia, Mycobacterium, Stapylococcus, Clostridioides, Vibrio, Yersinia, Helicobacter, Moraxellaのデータベース。
解析も可能です。

### NCBIで用いられているリファレンスゲノム
https://www.ncbi.nlm.nih.gov/genome/browse#!/prokaryotes/refseq_category:reference


### PubMLST
https://pubmlst.org/

ドラフトゲノムをアップロードすることで、さまざまな菌種のMLSが可能です（菌種によってはMLST以外の遺伝子型別が可能）。


<br>

## 解析関係の情報サイト
### Guide to bacterial genome assembly

https://github.com/rrwick/Trycycler/wiki/Guide-to-bacterial-genome-assembly

細菌ゲノムのアセンブリ法について、推奨の方法を解説しています。


### macでインフォマティクス
https://kazumaxneo.hatenablog.com/

各種解析ソフトの概要や、インストール、実行例が多数掲載されています。

