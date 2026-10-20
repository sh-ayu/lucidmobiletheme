# Lucid Mobile Settings の導入

1. このフォルダーの中身をGitHubの既存 `sh-ayu/lucidmobiletheme` のルートにアップロードします。pluginフォルダーの階層を保ちます。
2. KettuでテーマのLucidを選択したまま、PluginsのURL追加から次を入れます。
   https://raw.githubusercontent.com/sh-ayu/lucidmobiletheme/refs/heads/main/plugin/
3. Lucid Mobile Settingsを有効にして、そのプラグインの設定を開きます。
4. プリセットかHEX、背景表示、見えやすさ20〜85を設定して「適用」を押します。配色と背景画像が選択色から生成されます。

## 既に導入済みの場合（1.2.0）

今のリポジトリではこのフォルダーをLucid-Mobile-Uploadという名前で公開しています。同じ場所へ上書きアップロードしてください。
既存のプラグイン詳細でRefetchを押して更新し、設定上部に「修正版 1.2.0」と表示されたことを確認します。
既存のURL: https://raw.githubusercontent.com/sh-ayu/lucidmobiletheme/refs/heads/main/Lucid-Mobile-Upload/plugin/
色を選び直し、「色の反映強度」を70〜100にして「適用」を押してください。

テーマ用JSONのURLとプラグインのURLは別です。このプラグインURLは上記アップロード後に使えます。
「元のテーマに戻す」、またはプラグインの無効化で元のLucidへ戻せます。
テーマを更新した場合、更新を優先します。再度カスタマイズする場合は「適用」を押してください。

色のカスタマイズと静止背景用です。曲連動・音声解析・プレイヤー・統計は含みません。
配布JSの読み込み、設定ツリー、復元、型検査は分離テスト済みですが、この補助プラグインの実機動作は未検証です。
元のテーマは利用者から導入・外観の良好な報告を受けています。

## ライセンスとソース

AGPL-3.0-or-later。Spicetify Lucid: sanoojesとコントリビューター。
Material Color Utilities: Google LLC、Apache-2.0。
対応するソース・ビルド手順・検証記録は同梱Lucid-Mobile-Source.zipにあります。
LICENSE、THIRD_PARTY_NOTICES.mdとともに公開してください。
