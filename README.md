# corona_lifegame


## Overview

ライフゲームを模したコロナウィルス拡散のシミュレーション


## Rule

- 距離と伝染確率の関係は以下：

  - 半径＝１（隣マス）の人には 1/5 の確率で伝染する

  - 半径＝２（１つ間の空いたマス）の人には 1/25 の確率で伝染する

  - 半径＝３（２つ間の空いたマス）以上の距離にいる人には伝染しない

- 伝染した場合、1/5 の確率で重症化する

  - 重症化の有無と伝染確率には相関関係はない


## Licensing

This code is licensed under MIT.


## Copyright

2020 [K.Kimura @ Juge.Me](https://github.com/dotnsf) all rights reserved.
