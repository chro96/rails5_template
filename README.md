# rails5_template

## Features
* we can immediately use devise gem( with user model), rails_admin gem, mysql, slim, and ja.yml with rails5

## Installation

1. clone this repository
2. Run `bundle install`
3. Run `rails db:migrate`
4. insert these setting into my.cnf(mysql config file) to use utf8mb4
```
[mysqld]
innodb_file_format = Barracuda
innodb_file_per_table = 1
innodb_large_prefix
``` 
5. Start a server `rails s` and administer your data at [/admin](http://localhost:3000/admin).

## Configuration
* In config/application.rb, `config.i18n.default_locale = :ja`, so if you don't use Japanese, change this config.


## Japanese bellow 
Rails5でdeivese(Userモデルで作成), rails_admin, mysql, slim, とja.ymlでの日本語化がされたプロジェクトを開始できます。

インストール手順は上記のInstallationの項目を参照してください。
もし日本語を使わない場合は、config/application.rbの`config.i18n.default_locale = :ja`を変更して下さい。