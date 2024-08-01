+++
title = "Node.js"
chapter = false
weight = 300
+++

AWS CDK は Node.js (>= 10.13.0, バージョン 13.0.0 - 13.6.0 を除く) を使用します。
バージョンは長期サポート対象のもの (翻訳時点では 16.x) を推奨します。.

* Node.js をインストールするには [node.js](https://nodejs.org) のページをご覧ください。

    * __Windows__: 古いバージョンの Node.js がインストールされている場合、.msi のインストールを Administrator として実行する必要がある場合があります。


* すでに Node.js がインストールされている場合は、互換性のあるバージョンであることを確認します:

    ```
    node --version
    ```

    バージョンは >= 10.13.0 である必要があります:

    ```
    v10.3.0
    ```

{{< nextprevlinks >}}