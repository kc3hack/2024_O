# Chum Chum Evaluation
<!-- プロダクト名に変更してください -->
![アボカド](https://github.com/kc3hack/2024_O/assets/109881263/775e7e72-f6e1-4bd6-8b02-174a24cc60e4)

## チーム名
チーム○ アボカド
<!-- チームIDとチーム名を入力してください -->


## 背景・課題・解決されること

<!-- テーマ「関西をいい感じに」に対して、考案するプロダクトがどういった(Why)背景から思いついたのか、どのよう(What)な課題があり、どのよう(How)に解決するのかを入力してください -->
メンバーの一人の中にダンスサークルのメンバーがおり，日々ダンスの技術向上に勤しんでいた．<br>
そこでダンスの練習を行う際の問題に​着目し、簡単で長く使えるアプリを開発しようと考えたところから始ままった．<br>
<br>
一方日本の伝統技術は継承問題を抱えている．その問題の原因の一つに伝統文化の継承の難しさがあると考えている．<br>
京都などを中心にした伝統舞踊を​次世代に継承したいということが私たちの願いだ.​<br>
この技術を使用することによって色々な人に伝統舞踊を知ってもらいたいと考えている.


## プロダクト説明
<!-- 開発したプロダクトの説明を入力してください -->
ダンス採点アプリ<br>
<img width="254" alt="image" src="https://github.com/kc3hack/2024_O/assets/109881263/953cacc5-d449-47b8-bdf6-0e7b7e0a87e2">

TensolFlowというライブラリを使用している．<br>
このライブラリを使用することによって人体の部位，肩，目，鼻の位置などを検出できるようになっている．<br>
<img width="609" alt="image" src="https://github.com/kc3hack/2024_O/assets/109881263/7648c842-08a2-46a0-98c2-e0bcef20edd8">


使用方法としてはアプリの指定の手順に従ってアップロード画面まで進む．<br>
<img width="252" alt="image" src="https://github.com/kc3hack/2024_O/assets/109881263/b14a7ba3-89ab-4373-a8ff-53f15f5b289d">

アップロード画面では2本の動画をアップロードし，その任意の部位からの2本のベクトルから算出される角度が2本の動画の間でどれほど異なっているのかということを点数化している．<br>
 グラフィカル ユーザー インターフェイス, アプリケーション

自動的に生成された説明
<img width="253" alt="image" src="https://github.com/kc3hack/2024_O/assets/109881263/fb2b64f5-44b4-45de-ac4f-718b60115439">


これを使用し，ベクトルを計算することによって内積を計算する．<br>
これを使って角度を検出することによって手本との差異を検出している<br>
<img width="475" alt="image" src="https://github.com/kc3hack/2024_O/assets/109881263/0245a37f-0f03-4200-a2c0-23411a7a90f9">


## 操作説明・デモ動画
[デモ動画はこちら](https://www.youtube.com/watch?v=_FAA15ARmas)
<!-- 開発したプロダクトの操作説明について入力してください。また、操作説明デモ動画があれば、埋め込みやリンクを記載してください -->


## 注力したポイント
<!-- 開発したプロダクトの中で、特に注力して作成した箇所・ポイントについて入力してください -->
アプリ内容だけでなくデザインにもこだわっています．。​<br>
また体格差があっても計算が行えるように工夫をしました．​<br>

TensolFlowは任意の部位の座標を出すライブラリである．​<br>
よって例えば，同じポーズを行なったとしても体格差があった場合，座標だけて点数をつけると高得点がつかない．​<br>
そのためにベクトルを算出し，内積を求めている．​<br>



## 使用技術
TensolFlow
Android　Studio

<!-- 使用技術を入力してください -->


<!--
markdownの記法はこちらを参照してください！
https://docs.github.com/ja/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
-->
