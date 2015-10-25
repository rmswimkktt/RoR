# Ruby on Rails チュートリアル：サンプルアプリケーション

# 第３章

1. generateスクリプト  
  ```rails generate controller StaticPages home help --no-test-framework```  
  rails generate controller コントローラ名 ページ名 [ページ名] オプション  
  コントローラ名…キャメルケース(単語の頭文字を大文字)  
  作成されるファイルの中身は薄い。一から作成しても問題ない。  

  ```rails generate integration_test static_pages```
  rails generate integration_test スペック名
  スペック名…コントローラ名が良いかと

* ドメイン言語(Dimain Specific Language)  
  wikiより
  > DSL は、ある特定の領域（ドメイン）の問題を解決するために作られ、
  > それ以外の領域の問題を解くことは想定していない。

# 第６章

1. 命名規則

  コントローラ名→複数形  
  モデル名→単数形  
  テーブル名→複数形  
