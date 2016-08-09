# Ansibleとは？
- 構成管理ツールの1つ
- 下記点に優れる
 - 被管理サーバに専用のエージェントの設定が不要
 - 記述がシンプル
- 構成管理をする*管理サーバ*と、構成管理される*被管理サーバ*から成り立つ

# インストール方法
- 管理サーバは、*Mac*と*Linux*に対応（Windowsは、Ansible2.1以降の対応）。
- 被管理サーバは、*Mac*と*Linux*、*Windows*に対応。

## 管理サーバのインストール・設定方法
- 事前準備として、被管理サーバを1台用意すること（管理サーバ自体でも良い）

### Macの場合
```
# brew update
# brew install ansible
```


# 参考文献

## RedhatによるAnsible2.1の記事
https://www.redhat.com/ja/about/press-releases/rhjapan-red-hat-debuts-ansible-21-network-automation-containers-microsoft-windows-and-azure
