
# Docker Setup

## 前提環境
1. VSCODE のインストールされていること (インストールがまだの場合は <a href="https://github.com/record-dev/docker-setup-recipe/blob/main/install/vscode.md">VSCODE インストール方法</a> で環境構築してください)
2. Docker のインストールされていること (インストールがまだの場合は <a href="https://github.com/record-dev/docker-setup-recipe/blob/main/install/docker.md">Docker インストール方法</a> で環境構築してください)

## 構築手順

### 1. docker-compose.yml ファイルを 作成したフォルダに挿入
<img width="648" height="148" alt="image" src="https://github.com/user-attachments/assets/572c813e-ef43-449b-8501-b14ddd219623" />


### 2. 作成したフォルダ内の空白の部分で [Shift 長押し] + [マウス右クリック] を押して Codeで開く
<img width="594" height="529" alt="image" src="https://github.com/user-attachments/assets/61077880-3acf-4294-860e-cccf39d567b0" />


### 3. [Ctrl] + [Shift] + [@] ボタンを同時押しでターミナルが表示後、 以下のコマンドを実行する
```bash
docker compose up -d
```
https://github.com/user-attachments/assets/c4fd1c77-76ad-46eb-ae46-2e284e5e1fbb



### 4. Docker Desktop にて Containers カテゴリで生成されているか確認する
<img width="1237" height="598" alt="image" src="https://github.com/user-attachments/assets/705f6e17-0ddc-47ef-ab99-6249505c14c6" />

### 5. 起動していない場合は Start ボタンを押して起動する
<img width="392" height="333" alt="image" src="https://github.com/user-attachments/assets/5734fc4b-6f3f-43b0-9e45-d723d20a5fb3" />
