@title[Unityでタイピングゲームを作ってみよう]

@snap[west]
<h1>@size[0.7em](Unityで<br>タイピングゲームを<br>作ってみよう)</h1>
@snapend

---?image=assets/img/UnityHome.PNG&size=auto 65%&position=bottom
@title[Unityとは]

@snap[north-west]
<h2>@size[0.7em](Unityとは)</h2>
Unity公式サイト<a href="https://unity3d.com/jp">https://unity3d.com/jp</a>
@snapend

---?image=assets/img/Gaming.jpg&size=55% auto&position=right bottom
@title[Unityがあれば]

@snap[north-west]
<h2>@size[0.7em](Unityがあれば)</h2>
様々なゲーム機に対応したゲームが作れます
@snapend

@snap[south-west]
<ul>
  <li>@size[0.7em](iPhone)</li>
  <li>@size[0.7em](Android)</li>
  <li>@size[0.7em](PS4)</li>
  <li>@size[0.7em](PS Vita)</li>
  <li>@size[0.7em](WEB)</li>
  <li>@size[0.7em](Xbox)</li>
  <li>@size[0.7em](Facebook)</li>
  <li>@size[0.7em](...)</li>
</ul>
@snapend

---
@title[Unityで作られたゲームの一例]

@snap[north-west]
<h2>@size[0.7em](Unityで作られた有名ゲームの一例)</h2>
@snapend

@snap[west]
<ul>
  <li>スーパーマリオラン</li>
  <li>ポケモンGO</li>
  <li>いっしょにチョキッとスニッパーズ</li>
  <li>...</li>
</ul>
@snapend

@snap[south-west]
<b>モバイルゲーム向けの50%以上</b>がUnityで<br>
開発されています
@snapend

---
@title[Unityをダウンロードしよう]

@snap[north-west]
<h2>@size[0.7em](Unityをダウンロードしよう)</h3>
Unityは無料から使えます
@snapend

ダウンロードサイト
[https://store.unity.com/ja](https://store.unity.com/ja)

---?image=assets/img/UnityDownload.PNG&size=auto 60%&position=bottom
@title[プランを選ぼう]

@snap[north-west]
<h2>@size[0.7em](プランを選ぼう)</h2>
一番右の <b>Personal</b> が初心者向けです<br>
ダウンロードができたらインストールをしてください
@snapend


---
@title[早速つくってみよう]

@snap[west]
<h2>早速つくってみよう</h2>
@snapend

---
@title[アセットとは]

@snap[north-west]
<h2>@size[0.7em](アセットとは)</h2>
<p>
  <b>アセット</b>とはゲームの部品のこと<br>
</p>

<p>
  Unityアセットストア<br>
  <a href="https://www.assetstore.unity3d.com/jp/">@size[0.7em](https://www.assetstore.unity3d.com/jp/)</a><br>
  にて たくさんの人が無料から<br>
  アセットを提供しています<br>
</p>
@snapend

@snap[south-west]
今回は専用アセットを使って<br>
タイピングゲームを作っていきます
@snapend

---?image=assets/img/GitUnityPackage.PNG&size=53% auto&position=bottom right
@title[専用アセットをダウンロードする]

@snap[north-west]
<h2>@size[0.7em](専用アセットをダウンロードする)</h2>
ダウンロードページ<br>
<a href="https://github.com/yuki-thewaggle/EduvationSummit2018/blob/master/TheWaggleTypingGame.unitypackage">
  @size[0.7em](https://github.com/yuki-thewaggle/EduvationSummit2018/blob/master/TheWaggleTypingGame.unitypackage)
</a>
<p>
  中央の右寄りにある<br>
  **Download** ボタンを押して<br>
  ダウンロードしてください
</p>
@snapend

---?image=assets/img/UnityShortcut.PNG&size=15% auto
@title[unityを起動する]

@snap[north-west]
<h2>@size[0.7em](unityを起動する)</h3>
デスクトップのショートカットをダブルクリックして起動してください
@snapend

---?image=assets/img/CreateNewProject.PNG&size=auto 53%&position=right bottom
@title[新規プロジェクトを作成する]

@snap[north-west]
<h2>@size[0.7em](新規プロジェクトを作成する)</h3>
<ol>
  <li><i>Project name</i>を<b>TypingGame</b>に</li>
  <li><i>Location</i>を<b>自分がフォルダを保存したい場所</b>に</li>
  <li>他の項目はデフォルトのままで大丈夫です</li>
  <li><b>Create project</b>ボタンを<br>
    クリックして<br>
    プロジェクトを<br>
    作成してください</li>
</ol>
@snapend

---?image=assets/img/UnityLayout_after.png&size=auto 70%&position=bottom
@title[Unityエディタのレイアウトを設定する]

@snap[north-west]
<h2>@size[0.7em](Unityエディタのレイアウトを設定する)</h2>
このチュートリアルでは<b>Tall</b>を採用しています
@snapend

---?image=assets/img/UnityLayout_before.png&size=auto 70%&position=bottom
@title[レイアウト設定方法]

@snap[north-west]
<h2>@size[0.7em](レイアウト設定方法)</h2>
<b>Window</b> > <b>Layouts</b> > <b>Tall</b> を選択してください
@snapend

---?image=assets/img/ImportPackage0.png&size=auto 60%&position=bottom
@title[アセットを選択する1]

@snap[north-west]
<h2>@size[0.7em](アセットを選択する1)</h2>
<b>Assets</b> > <b>ImportPackage</b> > <b>CustomPackage...</b> をクリックしてください
@snapend

---
@title[アセットを選択する2]

@snap[north-west]
<h2>@size[0.7em](アセットを選択する2)</h2>

<p>
<b>TheWaggleTypingGame.unitypackage</b> を選択して
![選択するアセット](assets/img/ImportPackage.PNG)
</p>
<p>
<b>開く</b> ボタンをクリックしてください
![開くボタン](assets/img/ImportPackage2.PNG)
</p>
@snapend

---?image=assets/img/ImportPackage3.png&size=auto 70%&position=bottom
@title[アセットをインポートする]

@snap[north-west]
<h2>@size[0.7em](アセットをインポートする)</h2>
そのまま<b>Import</b>ボタンをクリックしてください
@snapend

---?image=assets/img/ImportedAssets.PNG&size=auto 60%&position=bottom
@title[インポートされたことを確認する]

@snap[north-west]
<h2>@size[0.7em](インポートされたことを確認する)</h2>
<i>Project</i> ウィンドウの <i>Assets</i> の中から<br>
これらのファイルが見えることを確認してください
@snapend

---?image=assets/img/NewScene.png&size=auto 60%&position=bottom
@title[新規シーンを作成する]

@snap[north-west]
<h2>@size[0.7em](新規シーンを作成する)</h2>
<b>File</b> > <b>New Scene</b> をクリックして<br>
新規シーンを作成してください
@snapend

---
@title[シーンとは]

<h2>@size[0.7em](シーンとは)</h2>

シーンとは、映画の1シーンの撮影セットのようなもの

舞台があって
その上にキャラクターや物があって
それをライトが照らし
カメラが映し出します

これら全てを
創ったり配置したりするのがシーンです

シーン上にあるカメラから映し出された映像が
ゲームの1シーンになります

---?image=assets/img/SaveScene.png&size=auto 60%&position=bottom
@title[シーンを保存する]

@snap[north-west]
<h2>@size[0.7em](シーンを保存する)</h2>
<b>File</b> > <b>Save Scene</b> をクリックしてください<br>
シーンに名前をつけて保存します
@snapend

---?image=assets/img/SaveScene2.PNG&size=60% auto
@title[シーン名を入力する]

@snap[north-west]
<h2>@size[0.7em](シーン名を入力する)</h2>
<b>ファイル名</b>に <b>Main</b> と入力して<br>
<b>保存</b> ボタンをクリックしてください
@snapend

---?image=assets/img/CreatedMain.PNG&size=auto 70%&position=bottom
@title[シーンが作成されたことを確認する]

@snap[north-west]
<h2>@size[0.7em](シーンが作成されたことを確認する)</h2>
このように <b>Main</b> と表示されれば保存成功です
@snapend

---
@title[プレハブをインスタンス化する]

@snap[north-west]
<h2>@size[0.7em](プレハブをインスタンス化する)</h2>
<p>
  <b>Assets</b> > <b>＿Prefabs</b> にある以下のものを<br>
  <b>Hierarchy</b>にドラッグ&ドロップしてください
</p>
<ul>
  <li>BackgroundMusic</li>
  <li>Floor</li>
  <li>GameManager</li>
  <li>HUDCanvas</li>
  <li>MainCamera</li>
  <li>MiniMapCamera</li>
  <li>Player</li>
</ul>
@snapend

---
@title[プレハブとインスタンス化]

<h2>@size[0.7em](プレハブとインスタンス化)</h2>
<p>
  プレハブとは、アセットの中でも<br>
  <b>部品化するだけでそのまま動き出す</b>ものです
</p>
<p>
  <i>Project</i> ウィンドウから <i>Hierarchy</i> ウィンドウに<br>
  ドラッグ&ドロップすることで<br>
  実際のオブジェクトになります
</p>
<p>
  この動作を<b>インスタンス化</b>といい<br>
  実体化されたオブジェクトを<b>インスタンス</b>といいます
</p>

---
@title[キー入力の設定]

<h2>@size[0.7em](キー入力の設定)</h2>
どのキー入力を何の処理として受け付けるかという設定

今回は、デフォルト設定の入力処理が
文字のタイピングと重複しないように消します

  - **Edit** > **ProjectSettings** > **Input** をクリック
    - **Axis**  > **Vertical** > **Horizontal** から **a** , **d** を消去
    - **Axis**  > **Vertical** > **Vercal** から **s** , **w** を消去

---
@title[スカイボックスの設定]

@snap[north-west]
<h2>@size[0.7em](スカイボックスの設定)</h2>
@snapend

  - **Window** > **Rendering** > **Lighting Settings** をクリック
    - **Skybox Material** のサークルセレクトをクリック
    - **NightmaresProceduralSkybox** をダブルクリック

---
@title[レイヤーの設定]
<h2>@size[0.7em](レイヤーの設定)</h2>
レイヤーとはゲームオブジェクトのグループ分けをするもの

今回は、マウスの位置を取得するためのオブジェクトを
レイヤーを利用して設定します

  - **Inspector** > **Layer** > **Add Layer** をクリック
    - 空いている一番上の欄に **Floor** と記入
    - **Hierarchy** > **Floor** > **MousePointingFloor** をクリック
    - レイヤーを **Floor** に設定

---
@title[ナビメッシュの設定]

<h2>@size[0.7em](ナビメッシュの設定)</h2>
ナビメッシュとはゲームオブジェクトが動く経路を
自動探索させるために設定する可動範囲のこと

  - **Hierarchy** > **Floor** > **NavMeshWalkableFloor** をクリック
    - **MeshRenderer** のチェックボックスを **チェックがついた状態** にする
  <!--  - **AddComponent** をクリックして **MeshRenderer** を選択-->
    - **Window** > **AI** > **Navigation** をクリック
    - **Bake** タブにある **Bake** ボタンをクリックする
    - **MeshRenderer** のチェックボックスを **チェックが外れた状態** にする

---
@title[MainCameraとDirectionalLightの削除]

<h2>@size[0.7em](MainCameraとDirectionalLightの削除)</h2>

シーンを新規作成したときに
デフォルトで生成されていたカメラとライトを
右クリックして **Delete** する

  - **Hierarchy** > **MainCamera** を削除
  - **Hierarchy** > **DirectionalLight** を削除

---
@title[シーンをリロードできるように設定]

<h2>@size[0.7em](シーンをリロードできるように設定)</h2>
ゲームオーバーになったときに
シーンがリロードされるように設定する

  - **File** > **Build Settings** をクリックする
    - **Add Open Scenes** をクリックする

---
@title[動きを確かめる]

<h2>@size[0.7em](動きを確かめる)</h2>

1. **Game** > **Maximize On Play** をクリックする
1. 動きを確かめる

  - @size[0.7em](矢印キーの押された方向にプレーヤーが動く)
  - @size[0.7em](マウスのある方向にプレーヤーが向く)
  - @size[0.7em](正しくキー入力をするとエネミーの問題文が赤文字に代わる)
  - @size[0.7em](エネミーの問題文をすべて入力するとエネミーが死ぬ)
  - @size[0.7em](エネミーはプレーヤーを自動で追いかけ続ける)
<!--  - @size[0.7em](プレーヤーもエネミーも障害物を避けて進む)-->
  - @size[0.7em](プレーヤーのHPが0になるとゲームオーバーになり リスタートする)

---
@title[問題なければ最後に]

<h2>@size[0.7em](問題なければ最後に)</h2>

1. **Project** > **Assets** > **＿Prefabs** > **Lights** をインスタンス化
1. **Project** > **Assets** > **＿Prefabs** > **Environment** をインスタンス化

<!--1. **Window** > **Rendering** > **Lighting Settings**をクリックする-->
<!--  - **Auto Generating** をクリックしてチェックを外す-->
<!--  - **Generate Lighting** をクリックする-->

---
@title[トライしてみよう]

<h2>トライしてみよう</h2>

---
@title[エネミーの問題文を変えるには]

<h2>@size[0.7em](エネミーの問題文を変えるには)</h2>

1. **Project** > **Assets** > **＿Resources** をクリックする
  - **TypingText** をダブルクリックする
  - 一行に一単語を入力する
    ※半角英字（小文字）だけを使う設定になっています
  - 保存する
1. **Project** > **Assets** > **＿Resources** をクリックする
  - **Inspector** で新しいデータに書き換わっていることを確認する

これでエネミーの問題文が新しいデータに変わります

---
@title[プレーヤーHPの設定]

<h2>@size[0.7em](プレーヤーのHP設定)</h2>

プレーヤーのHPを変える

1. **Hierarchy** > **Player** をクリック
  - **Inspector** > **Player Health Controller** > **Starting Health** の値を変更する
1. **Hierarchy** > **HUDCanvas** > **HealthUI** > **HealthSlider** をクリック
  - **Slider** > **MaxValue** を変更した値に変える
  - **Slider** > **Value** を最大値に変える

---
@title[プレーヤーのスピード設定]

<h2>@size[0.7em](プレーヤーのスピード設定)</h2>

プレーヤーの動くスピードを変える

1. **Hierarchy** > **Player** をクリック
1. **Inspector** > **Player Movement Controller** > **Speed** の値を変更する

---
@title[エネミーのスピード設定]

<h2>@size[0.7em](エネミーのスピード設定)</h2>

エネミーの動くスピードを変える

1. **Project** > **Assets** > **OtherPrefabs** > **Charactors** をクリック
1. スピードを変更したいエネミーをクリック
1. **Inspector** > **Enemy Movement Controller** > **Speed** の値を変更する

---?image=assets/img/Scripting2.PNG&size=100% auto&position=bottom
@title[スクリプトを触ってみる]

@snap[north-west]
<h2>@size[0.7em](スクリプトを触ってみる)</h2>

<b>Assets</b> > <b>Scripts</b> > <b>GameManager</b> > <b>GameController.cs</b> をダブルクリックして<br>
画像の通りに104行目に<b>Debug.Log()</b>を入れてみる
@snapend

---
@title[ゲームオブジェクトを作ってみる]

<h2>@size[0.7em](MiniMapを作ってみる)</h2>

1. **Hierarchy** > **MiniMapCamera** をクリックして **Inspector** 内の一番上にあるチェックを外す
1. **Hierarchy** > **Create** > **Camera** をクリック
1. 名前を **MiniMap** に変更
1. **Inspector**の全ての値を **MiniMapCamera** の通りに設定
1. 全体を真上から移すカメラとして動いていることを確認
