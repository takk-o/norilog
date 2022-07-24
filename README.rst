==============
乗りログアプリ
==============

目的
====
Webブラウザーでコメントを投稿するWebアプリケーションの練習

ツールのバージョン
==================
:Python:    3.10.5
:pip:       22.2

インストールと起動方法
======================
リポジトリーからコードを取得し、その下にvenv環境を準備します::

    $ git clone https://github.com/takk-o/norilog
    $ cd norilog
    $ python3.10-m venv venv
    $ source venv/bin/activate
    (venv) $ pip install .
    (venv) $ norilog
     * Running on http://127.0.0.1:8000/

開発手順
========
開発用インストール
------------------
1. チェックアウトする
2. 以下の手順でインストールする::

    (venv) $ pip install -e .
