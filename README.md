# ansible-mechatrax-playbook
メカトラックス株式会社のラズベリーパイ向け周辺機器を使用するための環境を構築する ansible の playbook です。

## 使い方
環境に合わせて hosts を編集してください。

コマンドを実行して環境構築を行います。

### Raspberry Pi OS に 4GPi のセットアップを行う場合
```
ansible-playbook -i hosts 4gpi.yml
```

### Raspberry Pi OS Legacy に 4GPi のセットアップを行う場合
```
ansible-playbook -i hosts 4gpi-legacy.yml
