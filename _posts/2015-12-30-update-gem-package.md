---
layout: post
title:  gemパッケージをバージョンアップする方法
date:   2015/12/30 16:16:00 +0900
categories: gem
---

gem自身ではなくて、gemパッケージ(railsなど)のバージョンを上げる方法を記載する。  
検索したらgem自身のバージョンアップ方法が上位にきて探しづらかったため。

パッケージの例としてrailsを利用する。

まずは、現在インストールされているrailsのバージョンを確認する。
```bash
gem list rails
```

以下が出力結果。
```
*** LOCAL GEMS ***

rails (4.2.2, 4.0.5)
```

バージョンを上げるため、以下を実行する。
```bash
gem update rails
```

インストールされているバージョンを確認して、上がっていることを確認する。
```
*** LOCAL GEMS ***

rails (4.2.4,　4.2.2, 4.0.5)
```

問題なくrailsがupdateされた。
