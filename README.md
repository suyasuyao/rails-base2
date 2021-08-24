# rails-base2
raiis開発のベースとなるプロジェクト



## 作り方

rails_base_app のところに作りたいアプリ名いれる
バージョンは5.2.6

```

rails _5.2.6_ new rails_base_app -d postgresql

```

以下を実施して動くの確認する。

```
cd rails_base_app/
rm -r .git
bin/rails s
```

ここでコミット
```


```


WebのDockerfileつくる
rubyコンテナを動かしてインストールする。

DbのDockerファイル作る
postgresコンテナを起動する

Dockercomposeファイル作る。