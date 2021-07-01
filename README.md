# A special seminar for Kato-lab memebers 
20210702 
講義サポート ページ  
場所：オンライン

### 特別資料  
[Computer Vision with Deep Learning for Plant Phenotyping in Agriculture: A Survey](https://arxiv.org/pdf/2006.11391.pdf)  
[二宮先生、私の国際化](https://www.jstage.jst.go.jp/article/shita/29/1/29_10/_pdf)  
[The Affective Growth of Computer Vision(CVPR2021)](https://openaccess.thecvf.com/content/CVPR2021/html/Su_The_Affective_Growth_of_Computer_Vision_CVPR_2021_paper.html)

## 質問は随時受け付けています ZoomのChatを活用ください　　

[おすすめ深層学習入門](https://youtu.be/W92VcivhoBs)
### [Study_CNN_Explainer](https://utokyo-fieldphenomics-lab.github.io/Study_CNN_Explainer/) (本日の講義用に修正した)  

original version from Here: [Zijie J. Wang et al., 2020](https://github.com/poloclub/cnn-explainer)  
we modified the training data and model for students with agriculture background.  
modified version can be [found here](https://github.com/UTokyo-FieldPhenomics-Lab/Study_CNN_Explainer). 
<br>  
  
  
### ハンズオン1：深層学習を味わってみよう  
#### 01　雑草の分類モデル見てみよう　
- [Model avaiable here](https://teachablemachine.withgoogle.com/models/1u_hCfzqq/)

#### 02　何か作ってみよう　[Google Teachable Machine](https://teachablemachine.withgoogle.com/)
1. [Google Teachable MachineでAIを体験してみよう](https://teachablemachine.withgoogle.com/)
2. データセット：  
[Rice Leaf Diseases Dataset](https://drive.google.com/drive/folders/1fVMMot1PXGeLIvw2OB6thkH3_jX9nSX3?usp=sharing), Resources from [here](https://www.kaggle.com/vbookshelf/rice-leaf-diseases) ;  
[flowers](https://drive.google.com/drive/folders/1oukB6MPBRcEejDhf1qphxcLcP4vcVSux?usp=sharing),Resources from [here](https://www.kaggle.com/alxmamaev/flowers-recognition) ;   
[V2 Plant Seedlings Dataset](https://drive.google.com/drive/folders/1hcN1MAa-KkLZvTUVJX-FhvXPEqRHusnK?usp=sharing),Resources from [here](https://www.kaggle.com/vbookshelf/v2-plant-seedlings-dataset) ;  
[Weeds_practice_Dataset](https://drive.google.com/drive/folders/1O5fx-mgyGC_-3Bl2Il0LnT9ouC7OCq0R?usp=sharing) ;  

  
<br>  

### ハンズオン2：深層学習による雑草の分類
Google Colaboratoryを利用する
- 雑草分類に関する深層学習のチュートリアル。
- Google Colaboratoryベースのノートブックです。 必要なのは、インターネット接続、Google Chromeブラウザ、およびGoogleアカウントだけです。 **クリックでGPU学習環境！**
- ノートブックを開くには、各セクションの ![image](https://colab.research.google.com/assets/colab-badge.svg)をクリックします。 コードのカスタマイズと保存には、GoogleアカウントにログインしてローカルのGoogleドキュメントフォルダーにipynbをコピーすることをお勧めします。

#### 1~4、順番で練習しましょう！
![badge](https://img.shields.io/badge/todo-orange.svg) Google Colaboratoryは必ずランタイムを初期化してから実行してください。
<br>  


#### 01　雑草の生育期間を区別せずに分類器を作る(2021修正)

 <img src = "asset/hakidamegiku_IMG_4877_5.jpg" width="150" ALIGN="left" />[![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oceam/FieldInfomatics-Lecture-2021/blob/master/notebook/weed_training_01.ipynb) <br>

雑草の生育期間（芽生え・生育済み）を区別せずに分類器を作成します。
育成した雑草の種類はハキダメギク、ホソアオゲイトウ、イチビ、イヌビエ、コセンダングサ、マメアサガオ、メヒシバ、オヒシバ、オイヌタデ、シロザの10種類です。  

<br>  

#### 02　雑草の生育期間を区別して分類器を作る（芽生え）(2021修正)

<img src = "asset/hakidamegiku_IMG_1546_2.JPG" width="150" ALIGN="left" /> [![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oceam/FieldInfomatics-Lecture-2021/blob/master/notebook/weed_training_02.ipynb) <br>

雑草の生育期間が芽生えのデータを用いて分類器を作成します。
育成した雑草の種類はハキダメギク、ホソアオゲイトウ、イチビ、イヌビエ、コセンダングサ、マメアサガオ、メヒシバ、オヒシバ、オイヌタデ、シロザの10種類です。  

<br>  

#### 03　雑草の生育期間を区別して分類器を作る（生育済み）(2021修正)

<img src = "asset/hakidamegiku_IMG_4877_5.jpg" width="150" ALIGN="left" /> [![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oceam/FieldInfomatics-Lecture-2021/blob/master/notebook/weed_training_03.ipynb) <br>

雑草の生育期間が生育済みのデータを用いて分類器を作成します。
育成した雑草の種類はハキダメギク、ホソアオゲイトウ、イチビ、イヌビエ、コセンダングサ、マメアサガオ、メヒシバ、オヒシバ、オイヌタデ、シロザの10種類です。  

<br>  

#### 04　科目が同じ品種をグループにして分類器を作る（生育済み）(2021修正)

<img src = "asset/hakidamegiku_IMG_1546_2.JPG" width="150" ALIGN="left" /> [![image](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oceam/FieldInfomatics-Lecture-2021/blob/master/notebook/weed_training_04.ipynb) <br>

雑草の生育期間が生育済みのデータを用いて分類器を作成します。
ハキダメギク、ホソアオゲイトウ、イチビ、イヌビエ、コセンダングサ、マメアサガオ、メヒシバ、オヒシバ、オイヌタデ、シロザの10種類の雑草のうち科目が同じのものを一つのclassにまとめるます。イネ科（イヌビエ、メヒシバ、オヒシバ）、キク科（ハキダメギク、コセンダングサ）とその他5種類に分けて分類器を作成します。  

<br>  



## Maintainers
Wei GUO (Oceam), 石井昌範.
東京大学国際フィールドフェノミクス研究拠点  
International Field Phenomics Research Laboratory, The University of Tokyo, Tokyo, Japan
