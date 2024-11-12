# よくある NiFi の処理パターン

このディレクトリの配下に、よくある NiFi の処理パターンを随時掲載予定です。

以下の形式で、みなさまからのフロー提供（プルリクエスト）も歓迎いたします。

```
common_patterns/     # このディレクトリ
├ 処理パターン名/  
　 ├ 処理パターン名.md  # フロー内容の説明  
　 ├ 処理パターン名.xml # NiFiにインポート可能なテンプレート
```

たとえば、list_fetchパターンのフローの場合、以下のような形式でこのディレクトリ内に配置します。

```
common_patterns/    
├ list_fetch/  
　 ├ list_fetch.md 
　 ├ list_fetch.xml
```