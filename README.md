# 絡繰喫茶 Apps & Tools

これまでに配布したアプリとDCCツールのダウンロード入口です。  
公開版の直接リンクは常にGitHub Releasesの最新版を参照します。開発版は説明に従ってください。

## すぐダウンロード

| 製品 | 用途 | Windowsで使うファイル | 更新履歴・ほかの形式 |
|---|---|---|---|
| **TM Tools for Maya** | Maya制作ツール一式 | [更新ZIPをダウンロード](https://github.com/KarakuriKissa/TM-Tools-Releases/releases/latest/download/TM_Tools_Maya_Update.zip) | [Maya専用ページ](https://karakuri-tools.karakurikissa.workers.dev/maya.html) ・ [リリース一覧](https://github.com/KarakuriKissa/TM-Tools-Releases/releases) |
| **TM Tools for Blender** | Blender制作ツール一式 | [初回インストール用ZIP](https://github.com/KarakuriKissa/TM-Tools-Releases/releases/latest/download/TM_Tools_Blender_Install.zip) | [Blender専用ページ](https://karakuri-tools.karakurikissa.workers.dev/blender.html) ・ [更新履歴](https://karakuri-tools.karakurikissa.workers.dev/releases.html) |
| **PicoPin** | 画面キャプチャ・注釈 | [PicoPin.exe](https://github.com/KarakuriKissa/PicoPin-releases/releases/latest/download/PicoPin.exe) | [リリース一覧](https://github.com/KarakuriKissa/PicoPin-releases/releases) |
| **ReplayRecorder** | アプリ起動をきっかけに、直近の指定時間を録画保存 | [ReplayRecorder.exe](https://github.com/KarakuriKissa/PicoPin-releases/releases/latest/download/ReplayRecorder.exe) | [リリース一覧](https://github.com/KarakuriKissa/PicoPin-releases/releases) |
| **PokeShelf** | アプリ・フォルダランチャー | [PokeShelf.exe](https://github.com/KarakuriKissa/PokeShelf-releases/releases/latest/download/PokeShelf.exe) | [リリース一覧](https://github.com/KarakuriKissa/PokeShelf-releases/releases) |
| **Toolporter** | アプリ・DCC・Windows設定をPC間で安全に引っ越す | [WindowsポータブルZIP](https://github.com/KarakuriKissa/Toolporter-releases/releases/latest/download/Toolporter_Windows_Portable.zip) | [リリース一覧](https://github.com/KarakuriKissa/Toolporter-releases/releases) |
| **Explorer Session Recorder** | 開いているExplorerフォルダーの自動記録・再表示 | [Windows ZIP](https://github.com/KarakuriKissa/ExplorerSessionRecorder-releases/releases/latest/download/ExplorerSessionRecorder.zip) | [リリース一覧](https://github.com/KarakuriKissa/ExplorerSessionRecorder-releases/releases) |
| **Soramado（開発版）** | 今夜の空を表示する星座盤 | [Android版APK](https://github.com/KarakuriKissa/soramado-builds/releases/download/android-preview-camera-20260910-083904/app-debug.apk) ※GitHubログインが必要 | [開発版リリース一覧](https://github.com/KarakuriKissa/soramado-builds/releases) ※非公開 |
| **PetaMemo** | デスクトップ付箋・タスク管理 | [Windowsセットアップ版](https://github.com/KarakuriKissa/sticky-todo/releases/latest/download/PetaMemo-Windows-Setup.exe) ・ [ポータブル版](https://github.com/KarakuriKissa/sticky-todo/releases/latest/download/PetaMemo-Windows-Portable.exe) | [Mac版](https://github.com/KarakuriKissa/sticky-todo/releases/latest/download/PetaMemo-Mac.dmg) ・ [リリース一覧](https://github.com/KarakuriKissa/sticky-todo/releases) |


## ブラウザで使うツール

| 製品 | 用途 | 最新版を開く |
|---|---|---|
| **3D文字ジェネレーター** | 文字の3Dモデルを作る | [Webツールを開く](https://fontgen.karakurikissa.workers.dev/) |
| **3D 福笑いジェネレーター β** | 顔パーツと登録したSTL・OBJを組み合わせ、STLを書き出す | [Webツールを開く](https://fontgen.karakurikissa.workers.dev/objects/) |

Webツールはダウンロード不要です。[アプリとWebツールの一覧](https://karakuri-apps.karakurikissa.workers.dev/)で公開中のツールを確認できます。

## TM Tools for Maya

### 初回導入・旧版からの更新

[Maya更新ZIPをダウンロード](https://github.com/KarakuriKissa/TM-Tools-Releases/releases/latest/download/TM_Tools_Maya_Update.zip)して展開し、中の `Update_TM_Tools.py` をMayaの3D画面へドラッグ＆ドロップします。初めてTM Toolsを入れるPCにも使えます。完了後にMayaを再起動してください。ZIP内の3ファイルは同じフォルダに置いたまま使います。

`tm_tools_maya.zip` は更新対象の本体です。これを単独でMayaへドラッグする必要はありません。

### 次回以降の更新

Mayaの **TM Tools → TM Toolsを更新... → 今すぐ更新** を使います。

## TM Tools for Blender

### 初回導入

1. [初回インストール用 `TM_Tools_Blender_Install.zip` をダウンロード](https://github.com/KarakuriKissa/TM-Tools-Releases/releases/latest/download/TM_Tools_Blender_Install.zip)する。
2. ZIPを展開せず、Blenderの **編集 → プリファレンス → アドオン → Install from Disk** で指定する。
3. アドオン一覧の **TM Tools Installer** を有効にする。ツール一式のダウンロードと導入が始まる。
4. 完了後にBlenderを再起動する。

### 次回以降の更新

3Dビューのサイドバー（Nキー）→ **tm System → tm Updater → Update tm Tools** を使います。`tm_tools_blender.zip` は初回用ではなく、InstallerとUpdaterが取得するツール本体です。Blenderの **Install from Disk** に選ぶファイルは `TM_Tools_Blender_Install.zip` です。

## GitHubトップからこの一覧を開く

GitHub右上のプロフィール画像を押し、**Your profile** を選びます。このページがプロフィール先頭に表示されます。
