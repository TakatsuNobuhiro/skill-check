# 概要
Apache HTTP Serverのサービスを自動起動するように設定するsystemd unitファイル

# 使い方


```
sudo systemctl daemon-reload
sudo systemctl enable httpd.service
sudo systemctl start httpd.service
```
システムの起動時にApache HTTP Serverが自動的に起動するようになる