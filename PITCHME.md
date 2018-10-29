##### タイピングゲームを作ってみよう
###### Unityでのタイピングゲーム開発
---
###### Unityとは(1/2)
---?image=assets/img/UnityHome.PNG&size=50%&color=lightgray&opacity=100

[Unity公式サイト](https://unity3d.com/jp)


- Unityがあれば様々なゲーム機に対応したゲームが作れます
  - iPhone
  - Android
  - PS4
  - PS Vita
  - WEB
  - Xbox
  - Facebook
  - ...

---
### Unityとは(2/2)

- Unityで作られた有名ゲーム
  - スーパーマリオラン
  - ポケモンGO
  - いっしょにチョキッとスニッパーズ
  - ...

- Unityは無料から使えます

---
### Unityをダウンロードしよう(1/2)

#### ダウンロードサイトにアクセスする
ダウンロードサイト　
[https://store.unity.com/ja](https://store.unity.com/ja)

---
### Unityをダウンロードしよう(2/2)
#### 初心者向け Personal を選ぶ
一番右側の **Personal** から **無料ダウンロード** をクリックする

![ユニティダウンロード](assets/img/UnityDownload?image=assets/assets/img/monkey.jpg&size=50% 100%&color=lightgray&opacity=100)

---
## 早速つくってみよう

---
### **アセット** をダウンロードする(1/3)

#### アセットとは

  - アセットとはゲームの部品のこと
  - Unityにはたくさんの人が無料からアセットを提供する[アセットストア](https://www.assetstore.unity3d.com/jp/)があります
  - 今回は専用アセットを使ってタイピングゲームを開発していきます

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
