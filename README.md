# sendgridjp-php-example

 本コードは[SendGrid公式PHPライブラリ](https://github.com/sendgrid/sendgrid-php)の利用サンプルです。

## 使い方

```bash
git clone http://github.com/sendgridjp/sendgridjp-php-example.git
cd sendgridjp-php-example
cp .env.example .env #  .nevファイルを編集してください
composer install
php -f sendgrid-php-example.php
php -f smtp-php-example.php
```

## .envファイルの編集
.envファイルは以下のような内容になっています。

```bash
SENDGRID_USERNAME=your_username
SENDGRID_PASSWORD=your_password
TOS=you@youremail.com,friend1@friendemail.com,friend2@friendemail.com
FROM=you@youremail.com
```
  SENDGRID_USERNAME:SendGridのユーザ名を指定してください。
  SENDGRID_PASSWORD:SendGridのパスワードを指定してください。
  TOS:宛先をカンマ区切りで指定してください。
  FROM:送信元アドレスを指定してください。


