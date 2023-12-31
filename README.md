# FantasyWizard3D

## 作成者	
佐生絢弥

## 所属 
バンタンゲームアカデミー大阪校ゲームプログラム総合

|開発の詳細||
----|----
|製作期間|75日(300時間)|
|制作時期|3年5月|
|制作人数|1人|
|ジャンル|3Dアクションゲーム|
|プレイ人数|1人|
|プレイ時間想定|30分|
|プラットフォーム|PC|
|言語|C++|

## 開発環境　　　　　　
Microsoft Visual Studio 
OpenGL
ImGui
Assimp

## 製作意図
自分の好きなファンタジーの世界観のゲームを作りたいと考えて作成しました。

## アプリケーションの内容
三人称視点の3Dアクションゲームで、騎士を操作して獣を狩るゲームです。現在は作成途中です。

## 起動方法
ExeFile/FantasyWizard.exeを起動してください

## 操作方法
- W,A,S,D　キャラクター移動
- マウス　カメラ移動
- 左クリック　攻撃
- ０キー　デバッグ画面
- 左コントロール　カメラ切り替え
- T　NPCと会話

## 終了方法
Escキーを入力

## 工夫した点
- Assimpでのアニメーションの再生をするにあたってゲームを作るためには重くなるので、キャッシュのような役割を作り、アニメーションやモデルをインスタンス描画することでフレームレートを30から60以上になるまで軽くしました。
- ImGuiでの文字列を送り文字で描画するために、UTF-8のグリフレンジを用意して、文字数を計算して描画することに成功しました。
- デバッグでの変更結果を別ファイルに保存しているので、入力の設定やキャラクターのステータス変更などをしやすくしました。
- カリングを作成し画面中のオブジェクトの数とすべてのオブジェクトの数を把握できるので、何が原因で重くなっているのかがわかりやすいです。

## イメージ画像

### デバッグ
<img src="https://github.com/june-mare/FantasyWizard/blob/master/ImageFile/Debug.png" alt="Debug" title="Debug" width="384" height="256">

### ライティング
<img src="https://github.com/june-mare/FantasyWizard/blob/master/ImageFile/Color.png" alt="Color" title="Color" width="384" height="256">

### ブルーム
<img src="https://github.com/june-mare/FantasyWizard/blob/master/ImageFile/Befor.png" alt="Befor" title="Befor" width="384" height="256">
<img src="https://github.com/june-mare/FantasyWizard/blob/master/ImageFile/After.png" alt="After" title="After" width="384" height="256">

### ブラー
<img src="https://github.com/june-mare/FantasyWizard/blob/master/ImageFile/Shader.png" alt="Shader" title="Shader" width="384" height="256">

### 会話　
<img src="https://github.com/june-mare/FantasyWizard/blob/master/ImageFile/Talk.png" alt="Talk" title="Talk" width="384" height="256">

## 自分がどのように頑張ったか
アニメーションを使ったゲームを作るために、授業で習っている範囲ではなくAssimpを使ってmixamoからモデルやアニメーションを取り入れられるように調べる力や、調べた結果いろんなやり方があった時にどのようにしたら自分がやりたいようにできるかを検証して作成できたところが頑張った点です。
