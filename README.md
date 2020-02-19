autoloadとeager_loadのテストサンプルアプリ

Rails4.2.11.1
Ruby2.5.7

lib以下にFooクラス定義

テストコマンド

- $ DISABLE_SPRING=true RAILS_ENV=production rails runner "Foo.new.foo"
