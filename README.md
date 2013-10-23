# HachiPAN

OrePAN of the Hachioji.pm!

## 使い方

HachiPAN は公開されているので、以下のような方法で利用することができます。

### cpanm を利用する場合

    $ cpanm --mirror=http://pan.hachiojipm.org/ --installdeps .

### carton を利用する場合

    PERL_CARTON_MIRROR=http://pan.hachiojipm.org/ carton install

## モジュールの加え方

大体、OrePAN2 のドキュメントに沿えば大丈夫です。ざっくり説明すると、

1. `authors/` 以下にモジュールを追加する (`orepan2-inject` を使っても良いし、手動でやってもよいでしょう。手動の場合はAutorの名前を適宜ディレクトリ名に反映してください)
2. `orepan2-indexer` を使ってインデキシングする

これでオッケー！
