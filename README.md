# azure-lamp-setup-guide

Microsoft Azureの仮想マシン(VM)上にLAMP環境(Linux + Apache + MySQL + PHP)を構築する手順書です。AWSでの`aws-lamp-setup-guide`に対応するAzure版として、実際にAzure for Studentsアカウントで行ったハンズオン作業をDocument as Code形式で記録しています。

## 内容

- リソースグループ・VM(Ubuntu 24.04)の作成手順
- VMサイズ選択時のクォータ制約とその対処法
- ネットワークセキュリティグループ(NSG)によるSSH/HTTPアクセス制御
- SSH接続、Apache/PHP/MySQLのインストールとMySQLユーザー作成
- 独自Webページの公開
- リソースグループ削除による後片付けとコスト確認
- AWSとの比較を通じた学び

## 関連リポジトリ

- [azure-fundamentals-notes](https://github.com/saki-nya1539/azure-fundamentals-notes) — Azure基礎知識まとめ
- [aws-lamp-setup-guide](https://github.com/saki-nya1539/aws-lamp-setup-guide) — AWSでのLAMP環境構築手順書
- [aws-lamp-terraform](https://github.com/saki-nya1539/aws-lamp-terraform) — AWS環境のTerraformコード
- [iac-ai-code-review](https://github.com/saki-nya1539/iac-ai-code-review) — 生成AIによるIaCコードレビュー練習記録
- [aws-fundamentals-notes](https://github.com/saki-nya1539/aws-fundamentals-notes) — AWS基礎知識まとめ
