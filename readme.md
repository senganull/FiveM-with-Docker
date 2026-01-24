
# Docker Setup

## 前提環境
1. Docker のインストールがされていること (インストールがまだの場合は <a href="https://github.com/record-dev/docker-setup-recipe/blob/main/install-docker.md">Docker 環境構築方法</a> で環境構築してください)
2. VSCODE のインストールができていること (インストールがまだの場合は <a href="https://github.com/record-dev/docker-setup-recipe/blob/main/install-vscode.md">VSCODE 環境構築方法</a> で環境構築してください)

## 構築手順

### 1. docker-compose.yml ファイルを 作成したフォルダに挿入
<img width="648" height="148" alt="image" src="https://github.com/user-attachments/assets/572c813e-ef43-449b-8501-b14ddd219623" />


### 2. 作成したフォルダ内でコマンドプロンプトを開く
<img width="511" height="411" alt="image" src="https://github.com/user-attachments/assets/8384200f-a09a-49b0-bee9-4380dccd9d8e" />


### 3. 以下のコマンドを実行する
```bash
docker compose up -d
```

### 4. Docker Desktop にて Containers カテゴリで生成されているか確認する
<img width="1237" height="598" alt="image" src="https://github.com/user-attachments/assets/705f6e17-0ddc-47ef-ab99-6249505c14c6" />

### 5. Start ボタンを押して起動する
<img width="392" height="333" alt="image" src="https://github.com/user-attachments/assets/5734fc4b-6f3f-43b0-9e45-d723d20a5fb3" />
