# 3Drepositorytest
test for 3D model browsing platform by GithubPages

#### Basic Concept
organising a simple web 3D model viewer with database for cultural heritage and museum collection  
based on web browsers, compatibility is not tested, but at least Google Chrome and Microsoft Edge are OK  
viewer: using Google ["<"model-viewer">"](https://modelviewer.dev/)  
3D models: mesh-texture models in .glb format, should be less than 20MB per file  
database: .csv, UTF-8  

#### optional  
- model selector
- language selector (for description)


[test page (Hida Sekibo)](https://kotdijian.github.io/3Drepositorytest/)

---

# 3Dリポジトリテスト
3Dモデル閲覧プラットフォームをGithubPagesから生成します  

#### 基本コンセプト
文化財・博物館資料向けのウェブベースのシンプルなモデルビューワーです  
Webブラウザ上で動作します。少なくともGoogle Chrome、Microsoft Edgeでの動作を確認しています  
Google ["<"model-viewer">"](https://modelviewer.dev/) で構築されています  
3Dモデルは.glb形式のメッシュ-テクスチャモデルです。1ファイルあたり20MB未満とします
説明文のデータベースは.csv形式、文字コードはUTF-8とします

#### 追加的機能
- プルダウンメニューによるモデル選択
- プルダウンメニューによる言語選択（日本語・英語）

[test page (Hida Sekibo)](https://kotdijian.github.io/3Drepositorytest/)

## どのように使えますか?
1. このリポジトリをFolkします（[どうやって?](https://docs.github.com/ja/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)）
2. Ownerは自分のアカウント (このリポジトリをFolkする先) を指定します
3. Folkしたリポジトリには別の名前を与えることもできます (デフォルトはFolk元の名前です)
4. **Create Folk** をクリックします
5. Folkしたリポジトリを開きます (自分のアカウントのプロフィールページにあります)
6. **models** フォルダを開き、右上の**Add File**ボタンから**Upload files**を選択
7. 公開したいGLBファイルをアップロードします (1ファイルあたり20MB以下)
8. Commit message (例: Add my 3D model) を入力後、**Commit Changes** ボタンをクリックします
9. アップロードしたGLBファイルのリンクを取得します (コピー可)
10. **DDB.csv** ファイルにGLBファイルのリンクを記入するか、外部でDDB.csvファイルを新たに作成しアップロードします
11. Folkしたリポジトリのトップに戻り、メニューバーの **Settings** をクリックします
12. 左側メニューカラムの **Pages** をクリックします
13. **Build and Deployment** を以下のとおり設定します (デフォルトの設定です)
    
    - Source = Deploy from a branch
    - select branch = main/ select folder = root
14. 上部の **Your site is live at** https://###.github.io/~~/ にURLが表示されます (###は自分のアカウント、~~はリポジトリ名です)
15. 上記のURLを開くと、ビューワーページを閲覧・操作できます (なおGithub pageの反映まで時間がかかる場合があります)
