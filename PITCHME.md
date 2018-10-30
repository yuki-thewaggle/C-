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
<b>モバイルゲーム向けの50%以上</b>が<br>Unityで開発されています
@snapend

---
@title[Unityをダウンロードしよう(1/2)]

@snap[north-west]
<h2>@size[0.7em](Unityをダウンロードしよう)</h3>
Unityは無料から使えます
@snapend

ダウンロードサイト
[https://store.unity.com/ja](https://store.unity.com/ja)

---?image=assets/img/UnityDownload.PNG&size=auto 65%&position=bottom
@title[Unityをダウンロードしよう(2/2)]

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
  Unityアセットストア（
  <a href="https://www.assetstore.unity3d.com/jp/">@size[0.7em](https://www.assetstore.unity3d.com/jp/)</a>
  ）にて<br>
  たくさんの人が無料からアセットを提供しています<br>
</p>
@snapend

@snap[south-west]
今回は専用アセットを使って<br>
タイピングゲームを作っていきます
@snapend

---?image=assets/img/GitUnityPackage.PNG&size=53% auto&position=bottom
@title[専用アセットをダウンロードする]

@snap[north-west]
<h2>@size[0.7em](専用アセットをダウンロードする)</h2>
ダウンロードページ<br>
<a href="https://github.com/yuki-thewaggle/EduvationSummit2018/blob/master/TheWaggleTypingGame.unitypackage">
  @size[0.7em](https://github.com/yuki-thewaggle/EduvationSummit2018/blob/master/TheWaggleTypingGame.unitypackage)
</a>
<p>
  中央の右寄りにある **Download** ボタンを押して<br>
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

---
@title[アセットを選択する]

@snap[north-west]
<h2>@size[0.7em](アセットを選択する)</h2>

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
ファイル名に <b>Main</b> と入力して<br>
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
  <b>Assets</b> > <b>_Prefabs</b> にある以下のものを<br>
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
  ドラッグ&ドロップすることで実際のオブジェクトになります
</p>
<p>
  この動作を<b>インスタンス化</b>といい<br>
  実体化されたオブジェクトを<b>インスタンス</b>といいます
</p>
<p>
<a href ="https://docs.unity3d.com/ja/current/Manual/Prefabs.html">@size[0.5em](プレハブ)</a><br>
<a href="https://docs.unity3d.com/ja/current/Manual/InstantiatingPrefabs.html">@size[0.5em](実行時のプレハブのインスタンス化)</a>
</p>

---
@title[その他の設定 1]

@snap[north-west]
<h2>@size[0.7em](その他の設定 1)</h2>
@snapend

- **Edit** > **ProjectSettings** > **Input** をクリック
  - **Axis**  > **Vertical** > **Horizontal** から **a** , **d** を消す
  - **Axis**  > **Vertical** > **Vercal** から **s** , **w** を消す

- **Window** > **Rendering** > **Lighting Settings** をクリック
  - **Skybox Material** のサークルセレクトをクリックして**NightmaresProceduralSkybox** にする

---
@title[その他の設定 2]

<h2>@size[0.7em](その他の設定 2)</h2>

- シーンを新規作成したときに自動生成される**MainCamera**と**DirectionalLight**を削除する

- **Hierarchy** > **MousePointingFloor** をクリック
  - レイヤーを**Floor**に設定

---
@title[その他の設定 3]

@snap[north-west]
<h2>@size[0.7em](その他の設定 3)</h2>
@snapend

- **Hierarchy** > **NavMeshWalkableFloor** をクリックする
  - **AddComponent**をクリックして**MeshRenderer**を選択する
  - **Window** > **AI** > **Navigation** をクリック
  - **Bake** タブにある **Bake** ボタンをクリックする
  - **MeshRenderer**のチェックボックスを**チェックが外れた状態**にする


---
@title[その他の設定 4]

@snap[north-west]
<h2>@size[0.7em](その他の設定 4)</h2>
@snapend

- **File** > **Build Settings** をクリックする
  - **Add Open Scenes** をクリックする

- **Window** > **Rendering** > **Lighting Settings**をクリックする
  - **Auto Generating** をクリックしてチェックを外す
  - **Generate Lighting** をクリックする


---
#### Playする

Maximize On PlayをONにする
動きを確かめる
(`_MyScene` > `MySceneTest`と同じだったらOK)

---

#### 問題なければ最後に

LightsとEnvironmentをインスタンス化する

---

#### 追記予定

- 問題文を変えるには
- プレーヤーの設定
- エネミーの設定
- スクリプトを触ってみる
- ゲームオブジェクトを作ってみる（MiniMapCamera）

---
@title[問題文を変えるには]

<h2>@size[0.7em](問題文を変えるには)</h2>

- **Project** > **Assets** > **＿Resources** をクリックする
  - **TypingText** をダブルクリックする
  - 一行に一単語を入力する
    - 半角英字（小文字）だけを使う設定になっています

---
@title[プレーヤーの設定]

<h2>@size[0.7em](プレーヤーの設定)</h2>

- プレーヤーの動くスピードを変える
  - **Hierarchy** > **Player** をクリック
  - **Inspector** > **Player Movement Controller** > **Speed**の値を変更する
- プレーヤーのHPを変える
  - **Hierarchy** > **Player** をクリック
  - **Inspector** > **Player Health Controller** > **Starting Health**の値を変更する

---
@title[エネミーのスピード設定]

<h2>@size[0.7em](エネミーのスピード設定)</h2>

- エネミーの動くスピードを変える
  - **Project** > **Asssets** > **OtherPrefabs** > **Charactors**をクリック
  - スピードを変更したいエネミーをクリック
  - **Inspector** > **Enemy Movement Controller** > **Speed**の値を変更する

---
@title[スクリプトを触ってみる]

<h2>@size[0.7em](スクリプトを触ってみる)</h2>

GameController.cs
InstanciateEnemy(){}にDebug.Logを入れてみる

---
@title[ゲームオブジェクトを作ってみる]

<h2>@size[0.7em](MiniMapを作ってみる)</h2>

1. MiniMapCameraのチェックを外す
1. Hierarchy > Create > Camera
1. 名前をMiniMapに変更
1. 各コンポーネントをMiniMapCameraの通りに設定
1. ちゃんと動くことを確認
1. プレハブ化
