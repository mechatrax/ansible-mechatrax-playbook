# ansible-mechatrax-playbook
メカトラックス株式会社のラズベリーパイ向け周辺機器を使用するための環境を構築する ansible の playbook です。

## 使い方
環境に合わせて hosts を編集してください。

コマンドを実行して環境構築を行います。

### 4GPi のセットアップを行う場合
```
ansible-playbook -i hosts 4gpi.yml
```

### 3GPi のセットアップを行う場合
```
ansible-playbook -i hosts 3gpi.yml
```
