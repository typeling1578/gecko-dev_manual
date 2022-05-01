# Firefoxのビルド方法

## Windows

### 必要条件
* メモリ: 最低4GB, **推奨8GB以上**
* ストレージ: 40GB以上の空き容量
* OS: Windows 10 か Windows 11

### セットアップ
#### 1. Visual Studio Build Tools 2022のインストール
Visual Studio Build Tools 2022をダウンロードし、インストールします。
インストールする際に、以下の項目にチェックをつけてください。
* 「ワークロード」タブで:
  * C++ によるデスクトップ開発
* 「個別のコンポーネント」タブで:
  * Windows 10 SDK (10.0.19041.0)
  * 最新のv143ビルドツール用C++ATL (x86およびx64)

#### 2. MozillaBuildのインストール

https://ftp.mozilla.org/pub/mozilla.org/mozilla/libraries/win32/MozillaBuildSetup-Latest.exe

これをダウンロードして、インストールします。

インストールが完了したら、インストール先にある「start-shell.bat」を実行してください。

#### 3. ソースコードのダウンロード
```
git clone [リポジトリのURL]
```
例えば、Firefoxなら、
```
git clone https://github.com/mozilla/gecko-dev
```

#### 4. mozconfigの作成
リポジトリのrootディレクトリに、```mozconfig```という名前のファイルを作成します。

メモ帳等で、下記のように記述します。
```
ac_add_options --enable-bootstrap
ac_add_options --with-branding=browser/branding/official
ac_add_options --enable-optimize="-O2"
ac_add_options --enable-release
ac_add_options --enable-rust-simd
```

#### 5. 初期化
手順2で開いたコンソールにて、リポジトリのrootディレクトリに移動します。

下記のコマンドを実行し、初期化します。
```
./mach bootstrap
```
するとビルドタイプを尋ねられるので、**この時必ず```2```を入力してください。**

途中で、git-cinnabarのセットアップをするか尋ねられるので、**この時必ず```y```を入力してください。**

最後の方で、Firefoxにコードの寄贈をするかなど尋ねられますが、今回は```n```を入力してください。

終わったら、下記のコマンドを実行し、初期化を完了させます。
```
./mach configure
```

#### 6. ビルド
下記のコマンドを実行し、ビルドを開始します。
```
./mach build
```
この作業は、非常に時間がかかります。
(このリポジトリのオーナーのPCでは、150分程度かかります。)

#### 7. 実行
ビルドが完了したら、下記のコマンドを実行すると、ビルドしたものが実行できます。
```
./mach run
```

## エラーなどが出て困った時は
気軽にIssueを立ててください。
