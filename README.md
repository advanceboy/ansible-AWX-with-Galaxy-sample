# ansible-AWX-with-Galaxy-sample

AWX 内での実行を想定した、サンプル ansible playbook 集です。

ブランチ毎に内容が異なります。

[sample-sleep-and-stat-playbook.yml](./sample-sleep-and-stat-playbook.yml) では、特定の時間スリープした後、変数でファイルパスが定義されていたらそのファイル情報を **「playbook を実行している端末」** で取得する構成コードを実行する playbook です。
