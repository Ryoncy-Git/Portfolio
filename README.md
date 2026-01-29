# ポートフォリオ
## 代表作
## 1.Blendshapeを一括でコピーするUnity拡張ツール
#### 概要
VRChatでの使用を想定し、UnityEditorの機能を用いてユーザーの補助をするツールを無償で配布しています。  
アニメーションファイルに登録されてるBlendshapeの情報をコピーするツールです。  

#### 実績
Pixiv Boothにて
- ♡ 900+
- 総DL数 700+

#### 開発背景
VRChat向けアバター改変において、表情やポーズシステムなど、あらゆるところでBlendshapeを含むアニメーションファイルの編集をすることになります。既存のツールでは一つ一つ手作業で登録する手法であり、私自身かなり不便に感じていました。無駄な作業時間や人的ミスを減らすためにこのツールを作成しました。30分かかる作業を3分で終わらせるために3時間かけて自分のために作成したツールですが、結果として多くの需要があり、たくさんの人の手助けになれたのではと感じています。

#### 技術的なポイント
- UnityEditorを用い、Unity内で操作が完結するようにしています。  
- AnimationClip内のカーブのうち"Blendshape"を含むものをコピーすることで実現しています。  
- 同一シェイプキーに関しては、上書きのルールをユーザー側で選択し、ユーザーの意図しないデータ破損を防いでいます。

#### 画像
![blendshape](https://github.com/Ryoncy-Git/Portfolio/blob/main/Blendshape.png)

#### リンク
[BoothのURLはこちら](https://ryoncy.booth.pm/items/7196296)

#### その他
他にもBoothにて、VRChat向けのUnity拡張ツールや3Dモデルなどを配布しています。  
[ノーマルマップ生成ツール](https://ryoncy.booth.pm/items/7598727) : ♡200+  
[ArmatureのTransformの情報を一括でコピーするツール](https://ryoncy.booth.pm/items/7384372) : ♡100+  
[Armatureを命名しなおすツール](https://ryoncy.booth.pm/items/7218733) : ♡220+  
[鳩ハット](https://ryoncy.booth.pm/items/6634736) : ♡50+  

---  

## 2.4Dテトリス
#### 概要
通常は二次元のテトリスを四次元まで拡張して再設計しました。   
[4DGolf](https://store.steampowered.com/app/2147950/4D_Golf/?l=japanese)というゲームから着想を得て、三次元までしか知覚できない制限の中で四次元構造をどう実装するかに重点を置いて制作しました。 

#### 画像
![テトリス](https://github.com/Ryoncy-Git/Portfolio/blob/main/4DTetris.png)

#### 技術的なポイント
- スクリプト内で四次元配列を用意し、処理した結果を三次元に丸めることで再現しています。
- 四次元に拡張することにより複雑に増えた操作方法を、ある程度操作しやすいよう搾っています。

#### リンク
- [Unityroom](https://unityroom.com/games/4dtetris)にて投稿しています。
- [GithubのURLはこちら](https://github.com/Ryoncy-Git/4DTetris)

---

## 3.御御御付ルーレット
#### 概要
御御御付（おみおつけ）の「御」の字の読み方をルーレット形式で決定するゲームを作りました。  
ユーモアとアニメーションを意識して開発しています。   

#### 画像
![御御御付](https://github.com/Ryoncy-Git/Portfolio/blob/main/Omiotsuke.png)

#### 制作意図
意味のないくだらないものを全力で作ることも、創作においては大切な一面だと考えています。  
自分の面白いと思ったことを表現できることが創作の良いところです。

#### リンク
[GithubのURLはこちら](https://github.com/Ryoncy-Git/OmiotsukeRoulette)

---

## 4.将棋
#### 概要
基本的な将棋のゲームです。  
機能追加やルール拡張を想定し、保守性を意識した構成で実装しています。  

#### 画像
![将棋](https://github.com/Ryoncy-Git/Portfolio/blob/main/Syougi.png)

#### リンク
[GithubのURLはこちら](https://github.com/Ryoncy-Git/Syougi)

---

## 5.レジスタンス
#### 概要
抵抗値から抵抗の回路を設計するゲームを制作中です。  
教育用としても利用できるパズルゲームのようなものを制作しようと考えています。  
ノードを使ってユーザーに分かりやすい実装をできるように意識しています。  　　

#### 画像
![抵抗](https://github.com/Ryoncy-Git/Portfolio/blob/main/Resistance.png)

#### リンク
[GithubのURLはこちら](https://github.com/Ryoncy-Git/Resistance)
