
# Docker Setup

## 前提環境
- Docker のインストールがされていること (インストールがまだの場合は <a href="https://github.com/NEKOPAN-R/docker-setup-recipe/blob/main/install-docker.md">こちら</a> で環境構築してください)

## 構築手順

1. docker-compose.yml ファイルを 作成したフォルダに挿入
   <img width="709" height="318" alt="image" src="https://github.com/user-attachments/assets/2e284ba1-f536-41d4-997a-d01a359af0d9" />

2. 作成したフォルダ内でコマンドプロンプトを開く
   <img width="677" height="512" alt="image" src="https://github.com/user-attachments/assets/9775edaf-57b1-4184-a53a-39882f596684" />

3. 以下のコマンドを実行する
```bash
docker compose up -d
docker compose up
```

4. Docker Desktop にて Containers カテゴリで生成されているか確認する
   <img width="1269" height="718" alt="image" src="https://github.com/user-attachments/assets/4f906930-6c1a-4f53-9672-e86c4710a33f" />

5. Start ボタンを押して起動する
<img width="397" height="280" alt="image" src="https://github.com/user-attachments/assets/f33cb76e-7de9-4f0d-9e35-45f833ac39d8" />
