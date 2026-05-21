# GitHub Pages 学習メモ

## 基本の流れ

1. **変更をステージング（git add）**
   - 変更したファイルを「次のコミット対象」として登録する
   - 例：`git add ファイル名` または `git add .`

2. **コミット（git commit）**
   - ステージングした変更をローカルリポジトリに記録する
   - 例：`git commit -m "コミットメッセージ"`

3. **プッシュ（git push）**
   - ローカルリポジトリの履歴をGitHubなどのリモートリポジトリに反映する
   - 例：`git push`

---

## GitHub Pages 公開手順（既存ディレクトリ利用）

1. 作業ディレクトリに移動
2. サイト用ファイルを用意（index.html, style.css, README.md など）
3. `git init`
4. `git add .`
5. `git commit -m "初回コミット"`
6. GitHubで新しいリポジトリを作成
7. `git remote add origin https://github.com/ユーザー名/リポジトリ名.git`
8. `git push -u origin main`
9. GitHubリポジトリの「Settings」→「Pages」で公開設定
10. 公開URLで確認

---

## 用語メモ

- **ステージング（add）**：変更を一時的に記録候補にする
- **コミット（commit）**：変更をローカル履歴に確定する
- **プッシュ（push）**：ローカル履歴をGitHubに反映する

---

> このファイルはGit/GitHub Pages学習用のメモです。必要に応じて追記・編集してください。
