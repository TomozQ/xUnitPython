### 3A
1. 準備（Arrange）: オブジェクトを作る
2. 実行（Act）: そのオブジェクトに対して操作を行う
3. アサート（Assert）: 結果の検証を行う

### テストで考えなければならないこと
#### パフォーマンス
テストは可能な限り速く動作してほしい。
例えば、同じようなオブジェクトを別々のテストで作成している際には、生成したオブジェクトを使いまわせないかと考えるものだ

#### 独立性
テストの成功/失敗は他のテストの結果に影響されたりしてほしくない。テスト間で共有されるオブジェクトが,
あるテストで変更されたら、後続のテストは結果が変わってしまう。