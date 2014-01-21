# HachiPAN

OrePAN of the Hachioji.pm!

## 使い方

HachiPAN は公開されているので、以下のような方法で利用することができます。

### cpanm を利用する場合

    $ cpanm --mirror=http://pan.hachiojipm.org/ --installdeps .

### carton を利用する場合

    PERL_CARTON_MIRROR=http://pan.hachiojipm.org/ carton install

## モジュールの加え方

手作業でtar ball配置するとか人間のやることではないのでコマンド使おう！

    $ orepan2-inject git://github.com:foo/Bar-Baz.git ./
    # 下はAUTHORの名前を指定するバージョン．METAとかちゃんとしてれば大丈夫
    $ orepan2-inject --author=HACHIOJIPM git://github.com:foo/Bar-Baz.git ./

