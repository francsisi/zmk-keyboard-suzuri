# SUZURI

SUZURIは文字通り書道で利用する「すずり」をイメージして作られたトラックボール付きキーボードです。その中でも特に小学生の頃に書道の道具セットに入っていて初めて手にしたような懐かしい感じをイメージしています。

メインのキーボードやマウスの脇に置いて使える、そんなものになれたらいいなと思いながら開発を進めてきました。

- ビルドガイド： https://note.com/snize/n/n124000b6199b
- 購入先： https://bulblub.booth.pm/items/7330554

## ファームウェアのダウンロード

[Releases](https://github.com/snize/zmk-keyboard-suzuri/releases) から`suzuri-seeeduino_xiao_ble-zmk.uf2`をダウンロードしてください。より新しい機能を試したい場合は、[Actions](https://github.com/snize/zmk-keyboard-suzuri/actions)内の成功しているWorkfowのArtifactsからzipをダウンロードしてください。

書き込み方については[ビルドガイド](https://note.com/snize/n/n124000b6199b)を確認してください。

## BLE 接続

通常のBLEデバイスと同様に、PCやスマートフォンから接続することができます。`SUZURI`というデバイス名で検出されます。

## カスタマイズ

ユーザが設定を変更する場合のためのテンプレートリポジトリ [zmk-suzuri-config-template](https://github.com/snize/zmk-suzuri-config-template) を用意しました。このページの右上の Use this template からご自身のリポジトリにコピーを作成し、必要に応じて config 内の `suzuri.conf` や `suzuri.keymap` を変更してください。

## サポート

サポートはDiscussionsで行っています。質問や問題がある場合は、[Discussions](https://github.com/snize/zmk-keyboard-suzuri/discussions)をご利用ください。

## 免責事項

このファームウェアは無保証です。自己責任でご利用ください。

## ライセンス

このリポジトリはMITライセンスで提供されています。詳細は[LICENSE](LICENSE)を参照してください。