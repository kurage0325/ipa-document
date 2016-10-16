# ipa-document


ドキュメント作成環境の構築（for Mac）
--------------------------------------------------------------------------------

※ 以下のコマンドを全て実行するシェルスクリプトは `GitHub Gist <https://gist.github.com/uns-miyama/1556bb84c9a8b88200452ad468f59f97>`_ にて公開。

※ Python、Homebrewのインストールは割愛

パッケージ管理 *pip* のインストール ::

  $ curl https://bootstrap.pypa.io/get-pip.py -o - | sudo python

パッケージ管理 *easy_install* のインストール ::

  $ curl https://bootstrap.pypa.io/ez_setup.py -o - | sudo python

Sphinxのインストール ::

  $ sudo easy_install sphinx sphinx-autobuild

ブロック図生成ツール *blockdiag* のインストール ::

  $ sudo brew install freetype
  $ sudo easy_install blockdiag
  $ sudo pip install sphinxcontrib-blockdiag

シーケンス図生成ツール *seqdiag* のインストール ::

  $ sudo pip install seqdiag
  $ sudo pip install sphinxcontrib-seqdiag

アクティビティ図生成ツール *actdiag* のインストール ::

  $ sudo pip install actdiag
  $ sudo pip install sphinxcontrib-actdiag

ネットワーク図生成ツール *nwdiag* のインストール ::

  $ sudo pip install nwdiag
  $ sudo pip install sphinxcontrib-nwdiag

テーマ *bizstyle* のインストール ::

  $ sudo easy_install sphinxjp.themes.bizstyle

