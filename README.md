# base-vagrant

vagrantを使いubuntuベースの作業環境を構築する。

## spec
virtualBox
|プロパティ|スペック|
---|---
|box|ubuntu/xenial64|
|private_network|172.16.10.10|
|gui|false|
|cpus|2|
|memory|2048|

ansible
- Docker-CE
- kubectl
- cloud SDK
- minikube
