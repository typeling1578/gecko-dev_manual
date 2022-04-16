# about:config

### alerts.showFavicons
type: Boolean

通知にFaviconを表示するかどうかを設定します。

true: 表示する
false: 表示しない


### alerts.useSystemBackend
type: Boolean

通知の表示にシステムのバックエンドを使用するかを設定します。

true: 使用する
false: 使用しない


### app.normandy.enabled
type: Boolean

[Normandy](https://support.mozilla.org/ja/kb/rate-your-firefox-experience-heartbeat)を有効にするかを設定します。

true: 有効
false: 無効


### app.normandy.first_run
type: Boolean

初回起動時に[Normandy](https://support.mozilla.org/ja/kb/rate-your-firefox-experience-heartbeat)による統計情報を送信するかを設定します。

true: 送信する
false: 送信しない


### app.update.channel
type: String

アップデートチャンネルを設定します。

例えば、```release```に設定すると、Firefoxのリリースバージョンのアップデートの確認を行います。


### beacon.enabled
type: Boolean

[Beacon](https://developer.mozilla.org/ja/docs/Web/API/Navigator/sendBeacon)を有効にするかを設定します。

true: 有効
false: 無効


### browser.aboutConfig.showWarning
type: Boolean

about:configを開いたときに警告を表示するかを設定します。

true: 表示する
false: 表示しない


### browser.download.useDownloadDir
type: Boolean

ダウンロード時にダウンロードディレクトリを使用するかを設定します。

true: 使用する
false: 使用しない


### browser.newtab.preload
type: Boolean

新しいタブを事前に読み込むかどうかを設定します。

true: 読み込む
false: 読み込まない


### browser.preferences.experimental
type: Boolean

設定に```実験的な機能```タブを表示するかを設定します。

true: 表示する
false: 表示しない


### browser.preferences.moreFromMozilla
type: Boolean

設定に```Mozilla からのご案内```タブを表示するかを設定します。

true: 表示する
false: 表示しない


### browser.preferences.search
type: Boolean

おそらく、設定に```検索```タブを表示するかを設定するものであるが、最新のFirefoxでは機能しないようです。

true: 表示する
false: 表示しない


### browser.privatebrowsing.autostart
type: Boolean

起動時にプライベートブラウジングモードを自動的に開始するかを設定します。

true: 有効
false: 無効


### browser.privatebrowsing.promoEnabled
type: Boolean

プライベートブラウジングモード時にMozilla VPNのプロモーションを表示するかを設定します。

true: 表示する
false: 表示しない


### browser.privatebrowsing.vpnpromourl
type: String

プライベートブラウジングモード時にMozilla VPNのプロモーションをクリックしたときに開かれるURLを設定します。


### browser.search.separatePrivateDefault.ui.enabled
type: Boolean

通常ウィンドウとプライベートウィンドウで使用する検索エンジンを別々に指定できるようにするかを設定します。

true: 指定できる
false: 指定できない


### browser.send_pings
type: Boolean

[ping属性](https://developer.mozilla.org/ja/docs/Web/HTML/Element/a#attr-ping=)を有効化するかを設定します。

true: 有効
false: 無効


### browser.sessionstore.warnOnQuit
type: Boolean

ブラウザーを終了するときに警告を表示するかを設定します。

しかし、この設定はESR91では機能しますが、最新のFirefoxでは機能しないようです。

true: 表示する
false: 表示しない


### browser.shell.checkDefaultBrowser
type: Boolean

起動時にデフォルトのブラウザに設定されているかを確認するかを設定します。

true: 確認する
false: 確認しない


### browser.startup.homepage
type: String
```browser.startup.homepage```が```1```に設定されているときに、起動後に表示するホームページを設定します。


### browser.startup.page
type: Integer

起動後に表示するページを設定します。

0~3の整数で指定します。

0: about:blankが開かれます。

1: browser.startup.homepageに設定されたページが開かれます。

2: 最後に開いたページが開かれます

3: 以前のセッションが復元されます。


### browser.tabs.closeTabByDblclick
type: Boolean

ダブルクリックでタブを閉じるかを設定します。

true: 閉じる
false: 閉じない


### browser.tabs.closeWindowWithLastTab
type: Boolean

最後のタブを閉じたときにウィンドウを閉じるかを設定します。

true: 閉じる
false: 閉じない


### browser.tabs.crashReporting.sendReport
type: Boolean

タブのクラッシュレポートを送信するかを設定します。

true: 送信する
false: 送信しない


### browser.tabs.warnOnClose
type: Boolean

ウィンドウを閉じるときに警告を表示するかを設定します。
しかし、ESR91では機能しないようです。

true: 表示する
false: 表示しない


### browser.tabs.warnOnCloseOtherTabs
type: Boolean

他のタブを一度に閉じるときに警告を表示するかを設定します。

true: 表示する
false: 表示しない


### browser.urlbar.update2.engineAliasRefresh
type: Boolean

検索エンジンの設定から任意の検索エンジンを追加可能にするか設定します。

true: 追加可能
false: 追加不可


### browser.urlbar.trimURLs
type: Boolean

URLバーのURLの```http://```などを省略するかを指定します。

true: 省略する
false: 省略しない


### datareporting.healthreport.uploadEnabled
type: Boolean

ヘルスレポートを送信するかを設定します。

true: 送信する
false: 送信しない


### datareporting.policy.dataSubmissionEnabled
type: Boolean

ヘルスレポートを送信するかを設定します。

true: 送信する
false: 送信しない


### default-browser-agent.enabled
type: Boolean

[default-browser-agent](https://firefox-source-docs.mozilla.org/toolkit/mozapps/defaultagent/default-browser-agent/index.html)を有効にするかを設定します。


### device.sensors.enabled
type: Boolean

[Sensor APIs](https://developer.mozilla.org/en-US/docs/Web/API/Sensor_APIs)を有効にするかを設定します。

true: 有効
false: 無効


### device.storage.enabled
type: Boolean

[DeviceStorageAPI](https://wiki.mozilla.org/WebAPI/DeviceStorageAPI)を有効にするかを設定します。

true: 有効
false: 無効


### dom.battery.enabled
type: Boolean

[Battery Status API](https://developer.mozilla.org/en-US/docs/Web/API/Battery_Status_API)を有効化するかを指定します。

true: 有効
false: 無効


### dom.ipc.processCount
type: Integer

ページの表示に使用するプロセス数を設定します。


### dom.ipc.processCount.extension
type: Integer

アドオンの読み込みに使用するプロセス数を設定します。

注意: この設定を変更すると、アドオンが読み込まれなくなります。


### extensions.pocket.enabled
type: Boolean

Pocketを有効にするかを設定します。

true: 有効
false: 無効


### extensions.webextensions.restrictedDomains
type: String

アドオンの動作を拒否するドメインを設定します。


### font.name-list.emoji
type: String

絵文字に使用するフォントを設定します。

例えば、```Twemoji Mozilla```と設定すると、[twemoji-colr](https://github.com/mozilla/twemoji-colr)が使用されます。


### geo.enabled
type: Boolean

[Geolocation API](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API)を有効化するかを設定します。

true: 有効
false: 無効


### gfx.webrender.all
type: Boolean

すべてのwebrenderを有効にするかを設定します。

true: 有効
false: 無効


### identity.fxaccounts.enabled
type: Boolean

Firefox Accountでのログインを有効にするかを設定します。

true: 有効
false: 無効


### image.avif.enabled
type: Boolean

AVIFのデコードを有効にするかを設定します。

true: 有効
false: 無効


### image.avif.use-dav1d
type: Boolean

AVIFのデコードにdav1dを使用するかを設定します。

true: 使用する
false: 使用しない


### image.webp.enabled
type: Boolean

WEBPのデコードを有効にするかを設定します。

true: 有効
false: 無効


### layout.css.backdrop-filter.enabled
type: Boolean

[backdrop-filter](https://developer.mozilla.org/ja/docs/Web/CSS/backdrop-filter)を有効化するかを設定します。

しかし、最新のFirefoxでは機能しないようです。

true: 有効
false: 無効


### media.av1.enabled
type: Boolean

AV1をサポートするかを設定します。

true: サポートする
false: サポートしない


### media.av1.use-dav1d
type: Boolean

AV1のデコードにdav1dを使用するかを設定します。

true: 使用する
false: 使用しない


### media.encoder.webm.enabled
type: Boolean

WEBMのエンコードを有効にするかを設定します。

true: 有効
false: 無効


### media.ffvpx.enabled
type: Boolean

ffvpxを有効にするかを設定します。

true: 有効
false: 無効


### media.ffvpx.mp3.enabled
type: Boolean

MP3をサポートするかを設定します。

true: サポートする
false: サポートしない


### media.flac.enabled
type: Boolean

FLACをサポートするかを設定します。

true: サポートする
false: サポートしない


### media.gmp-gmpopenh264.enabled
type: Boolean

OpenH264によるH264をサポートをするかを設定します。

true: サポートする
false: サポートしない


### media.gmp-widevinecdm.enabled
type: Boolean

WidevineによるDRMのサポートを有効にするかを設定します。

true: 有効
false: 無効


### media.gmp.decoder.aac
type: Boolean

AACをサポートするかを設定します。

true: 有効
false: 無効


### media.gmp.decoder.h264
type: Boolean

H264のデコードを有効にするかを設定します。

true: 有効
false: 無効


### media.hls.enabled
type: Boolean

HLSをサポートするかを設定します。

true: サポートする
false: サポートしない


### media.mp4.enabled
type: Boolean

MP4をサポートするかを設定します。

true: サポートする
false: サポートしない


### media.ogg.enabled
type: Boolean

OGGをサポートするかを設定します。

true: サポートする
false: サポートしない


### media.opus.enabled
type: Boolean

OPUSをサポートするかを設定します。

true: サポートする
false: サポートしない


### media.wave.enabled
type: Boolean

WAVEをサポートするかを設定します。

true: サポートする
false: サポートしない


### media.webm.enabled
type: Boolean

WEBMをサポートするかを設定します。

true: サポートする
false: サポートしない


### privacy.resistFingerprinting.block_mozAddonManager
type: Boolean

addons.mozilla.orgでアドオンを動作させるかを設定します。

true: アドオンを動作させる
false: アドオンを動作させない


### privacy.userContext.enabled
type: Boolean

コンテナータブを有効化するかを設定します。

true: 有効
false: 無効


### privacy.userContext.ui.enabled
type: Boolean

コンテナータブの設定をするUIを有効化するかを設定します。

true: 有効
false: 無効


### privacy.userContext.extension
type: String

コンテナータブを必要とするアドオンのIDが設定されています。


### svg.disabled
type: Boolean

SVGをサポートするかを設定します。

true: サポートしない
false: サポートする


### svg.context-properties.content.enabled
type: Boolean

SVGの色をCSSから変更できるようにするかを設定します。

true: 有効
false: 無効


### toolkit.legacyUserProfileCustomizations.stylesheets
type: Boolean

カスタムCSSを有効化するかを設定します。

true: 有効
false: 無効


### toolkit.telemetry.enabled
type: Boolean

テレメトリーを有効にするかを設定します。

true: 有効
false: 無効


### webgl.disabled
type: Boolean

WebGLをサポートするかを設定します。

true: サポートしない
false: サポートする


### xpinstall.signatures.required
type: Boolean

xpiファイルをインストールする際に署名が必要かを設定します。

しかし、この設定はFirefox Release、Firefox Betaでは機能しません。Firefox Developer Edition、Firefox Nightly、Firefox ESRでのみ利用できます。

true: 署名が必要
false: 署名が不要
