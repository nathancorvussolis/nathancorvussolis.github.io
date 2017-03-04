
| プログラム | バージョン | 日付 | 説明 |
|---|---|---|---|
| [CorvusSKK](https://github.com/nathancorvussolis/corvusskk) | [2.5.1](https://github.com/nathancorvussolis/corvusskk/releases/tag/2.5.1) | 2017/02/26 | Windowsで動作するSKK風のIMEです<br>[マニュアル](https://github.com/nathancorvussolis/corvusskk/blob/2.5.1/README.md)<br>[設定サンプル](https://github.com/nathancorvussolis/corvusskk/tree/2.5.1/installer/config-sample) |
| [crvskkserv](https://github.com/nathancorvussolis/crvskkserv) | [2.2.0](https://github.com/nathancorvussolis/crvskkserv/releases/tag/2.2.0) | 2016/04/16 | SKK辞書サーバー<br>Google CGI API for Japanese Inputにも対応 |
| [meskkdic](https://github.com/nathancorvussolis/meskkdic) | [2.2.0](https://github.com/nathancorvussolis/meskkdic/releases/tag/2.2.0) | 2016/04/16 | SKK辞書メンテナンスツール<br>SKK辞書の結合と差分の取得を行います |
| [cveuc](https://github.com/nathancorvussolis/cveuc) | [2.2.0](https://github.com/nathancorvussolis/cveuc/releases/tag/2.2.0) | 2016/04/16 | 文字コード変換ツール<br>EUC-JIS-2004、UTF-8、UTF-16に対応 |
| [pcrvskkserv](https://github.com/nathancorvussolis/pcrvskkserv) | 0.0.2 | 2016/11/30 | Python SKK辞書サーバー |
| [ncrvskkserv](https://github.com/nathancorvussolis/ncrvskkserv) | 0.4.0 | 2016/11/30 | Node.js SKK辞書サーバー |
| [skkdic](https://github.com/nathancorvussolis/skkdic) | ----- | 2017/03/01 | 雑多なSKK辞書と<br>http://openlab.ring.gr.jp/skk/skk/dic/ のミラー |
| [skkime-archive](https://github.com/nathancorvussolis/skkime-archive) | ----- | 2016/11/13 | SKKIME 98, 1.0, 1.5 と SKKIME 1.5 改 |

### お知らせ

* [Chocolatey](https://chocolatey.org/)からインストール可能になりました。https://chocolatey.org/packages/corvusskk (2016/05/17)

* [CorvusSKK 2.3.0](https://github.com/nathancorvussolis/corvusskk/releases/tag/2.3.0)にてLuaスクリプトファイルのインターフェイスを変更しました。カスタマイズされている場合は更新をお願いします。
  * SKK辞書検索のcrvmgr.search_skk_dictionary関数に送り仮名の引数を追加しています。
  * 詳しくは、[init.luaのdiff](https://github.com/nathancorvussolis/corvusskk/commit/360f2e12319c8cae812c1a428ea4ae2f80aa0f5b#diff-4ed04d9f881b697acf01312c3d80f743)をご覧ください。

* [CorvusSKK 2.3.0](https://github.com/nathancorvussolis/corvusskk/releases/tag/2.3.0)にて取込済SKK辞書のファイル名を変更しました。
  * 変更前の取込済SKK辞書が存在する場合は自動的に変更後の取込済SKK辞書が生成されるので、再度の取込処理は必要ありません。
    * 変更前 : skkdict.dic, skkdict.idx
    * 変更後 : skkdict.txt

* [CorvusSKK 2.1.0](https://github.com/nathancorvussolis/corvusskk/releases/tag/2.1.0)にてIMEのONとOFFをそれぞれ別々に設定できるようにしました。
  * 既存の設定ファイルはそのまま流用可能です。
  * 詳しくは、[config.xmlのサンプルのdiff](https://github.com/nathancorvussolis/corvusskk/commit/a12bc4c1e72bf34866e93a4131e3fcd0f91f39b8#diff-3b6dfa77bbb7a2f52ef0ece867c79834)をご覧ください。

* [CorvusSKK 1.8.5](https://github.com/nathancorvussolis/corvusskk/releases/tag/1.8.5)にてデフォルトのキー設定を一部変更しました。

  * Ctrl + Enter をアプリケーション側に通すようにする修正です。
  * 詳しくは、[config.xmlのサンプルのdiff](https://github.com/nathancorvussolis/corvusskk/commit/8b4e6889bd644055b6e60fdf15bf2a3b13532488#diff-3b6dfa77bbb7a2f52ef0ece867c79834)をご覧ください。

* [CorvusSKK 1.7.12](https://github.com/nathancorvussolis/corvusskk/releases/tag/1.7.12)にてローマ字仮名変換表の内部構造を変更しました。

  * ローマ字入力の場合は、バージョンアップのときにローマ字仮名変換表に「n、ん、ン、ﾝ」の行を追加してください。追加する場所は何行目でもOKです。
  * ローマ字仮名変換表のローマ字「nb」,「nc」,「nd」〜「nz」の行は不要となりますが、あっても問題ありません。
  * 詳しくは、[kanatable.txtのサンプルのdiff](https://github.com/nathancorvussolis/corvusskk/commit/b6a4f14363ca25f2390f9e45cca95ae8fd20ee1d#diff-6e3939736bb31470e55c3440f0501289)をご覧ください。

### 開発支援のお願い

開発環境、書籍を購入するための支援をお願いしています。

[Amazonギフト券Eメールタイプ](https://www.amazon.co.jp/gp/product/B004N3APGO/)を作者メールアドレス ``nathancorvussolis@gmail.com`` 宛に購入ください。15円から金額を指定することが可能です。

皆様のご協力に感謝します。