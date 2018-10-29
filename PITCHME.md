@title[Unityでタイピングゲームを作ってみよう]

@snap[west]
<h1>@size[0.7em](Unityで<br>タイピングゲームを<br>作ってみよう)</h1>
@snapend

---?image=assets/img/UnityHome.PNG&size=auto 65%&position=bottom
@title[Unityとは]

@snap[north-west]
<h2>@size[0.7em](Unityとは)</h3>
<a href="https://unity3d.com/jp">@size[0.7em](Unity公式サイト)</a>
@snapend


---?image=assets/img/Gaming.jpg&size=60% auto&position=right bottom
@title[Unityがあれば]

@snap[north-west]
<h2>@size[0.7em](Unityがあれば)</h3>
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
<h2>@size[0.7em](Unityで作られた有名ゲームの一例)</h3>
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
<b>モバイルゲーム向けの50%以上</b>がUnityで開発されています
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
<h2>@size[0.7em](プランを選ぼう)</h3>
一番右の <b>Personal</b> が初心者向けです
@snapend


---
@title[早速つくってみよう]

@snap[west]
<h2>早速つくってみよう</h2>
@snapend

---
@title[アセットとは]

@snap[north-west]
<h2>@size[0.7em](アセットとは)</h3>
今回は専用アセットを使ってタイピングゲームをつくっていきます
@snapend

@snap[south-west]
<b>アセット</b>とはゲームの部品のこと<br>
Unityにはたくさんの人が無料からアセットを提供する<a href="https://www.assetstore.unity3d.com/jp/">アセットストア</a>があります
@snapend


---
### **アセット** をダウンロードする(2/3)

#### 専用アセットをダウンロードする

[こちらのページ](https://github.com/yuki-thewaggle/EduvationSummit2018/blob/master/TheWaggleTypingGame.unitypackage)にアクセスすると以下の画面が出ます

---
### **アセット** をダウンロードする(3/3)

  ![アセットダウンロード](assets/img/GitUnityPackage.PNG)

中央の右寄りにある **Download** ボタンを押してダウンロードしてください

---
### unityを起動する

デスクトップのショートカットをダブルクリックして起動してください

  ![ショートカット](asets/img/UnityShortcut.PNG)

---
### 新規プロジェクトを作成する(1/2)

新規プロジェクトを作成します

![ショートカット](assets/img/CreateNewProject.PNG)

---
### 新規プロジェクトを作成する(2/2)

1. `Project name` を **TypingGame** にします
1. `Location` を **自分がフォルダを保存したい場所** にします
1. 他の項目はデフォルトのままで大丈夫です

以上3点が設定出来たら **Create project** ボタンをクリックしてプロジェクトを作成してください

---
### Unityエディタのレイアウトを設定する(1/3)

このチュートリアルで採用する **Tall** レイアウトに変更します

---
### Unityエディタのレイアウトを設定する(2/3)

最初はこのような状態になっていると思います

![デフォルトのレイアウト](assets/img/UnityLayout_before.PNG)

---
### Unityエディタのレイアウトを設定する(3/3)

**Window** > **Layouts** > **Tall** を選択してください

![変更後のレイアウト](assets/img/UnityLayout_after.PNG)

このようになります

---
#### Unityにアセットをインポートする(1/4)

先ほどダウンロードした専用アセットをインポートします

---
#### Unityにアセットをインポートする(2/4)

![選択するアセット](assets/img/ImportPackage.PNG)


**TheWaggleTypingGame.unitypackage** を選択して

---
#### Unityにアセットをインポートする(3/4)

![開くボタン](assets/img/ImportPackage2.PNG)

**開く** ボタンをクリックしてください

インポートするファイルの選択画面が出てきます

---
#### Unityにアセットをインポートする(4/4)

![開くボタン](assets/img/ImportPackage3.png)

デフォルトの状態で **Import** ボタンをクリックしてください

---

### Projectウィンドウからアセットを使う

インポートしたアセット（ゲームの部品）を利用してゲームを作成していきます

---
#### Projectウィンドウにアセットがインポートされたことを確認する

`Project`ウィンドウの `Assets` の中に画像のようなファイルが展開されていることを確認してください

![インポートしたアセット](assets/img/ImportedAssets.PNG)

---
### シーンを作る(1/5)

自分のシーンを作ります

---
### シーンを作る(2/5)

![新規シーン作成](assets/img/Newscene.PNG)

**File** > **New Scene** をクリックして新規シーンを作成してください

---
### シーンを作る(3/5)

![シーン保存](assets/img/Savescene.PNG)

次に **File** > **Save Scene** をクリックしてシーンを保存してください

---
### シーンを作る(4/5)

![シーン名入力](assets/img/Savescene2.PNG)

ファイル名に **Main** と入力して **保存** ボタンをクリックしてください

---
### シーンを作る(5/5)

![シーン作成確認](assets/img/CreatedMain.PNG)

このように **Main** と表示されれば保存成功です

---

### Prefab

#### prefabとは

---
#### インスタンスにする(1/2)

Projectウィンドウにあるアセットを実際の部品として生成します

---
#### インスタンスにする(2/2)
**Assets** > **_Prefabs** にある 以下のものをすべて **Hierarchy** にドラッグ&ドロップしてください

- BackgroundMusic
- Floor
- GameManager
- HUDCanvas
- MainCamera
- MiniMapCamera
- Player

---
### その他の設定

- **Edit** > **ProjectSettings** > **Input** をクリック
  - **Axis**  > **Vertical** > **Horizontal** から **a** キー, **d** キーを消す
  - **Axis**  > **Vertical** > **Vercal** から **s** キー, **w** キーを消す

- **Window** > **Rendering** > **Lighting Settings** の **Skybox Material** を
**Assets** > **NightmaresProceduralSkybox** にする


MousePointingFloor を　Floorにレイヤー設定

- **Window** > **AI** > **Navigation**

  - NavMeshWalkableFloorのBakeをする(MeshRendererをONにしてからNavigationウィンドウでそのままBakeボタンを押すだけ)

- シーンを新規作成したときに自動生成されるMainCameraとDirectionalLightを削除


---
#### Playする

Maximize On PlayをONにする
動きを確かめる
(`_MyScene` > `MySceneTest`と同じだったらOK)


---

#### 問題なければ最後に

LightsとEnvironmentをインスタンス化する

---

### 問題文を変えるには
### プレーヤーの設定
### エネミーの設定
### スクリプトを触ってみる
