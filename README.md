# GitHub Pages公開手順（既存ディレクトリ利用）

このリポジトリは、既存の作業ディレクトリを使ってGitHub Pagesで静的サイトを公開する手順例です。

## 公開までのステップ

1. **作業ディレクトリに移動**

   ```sh
   cd /パス/既存ディレクトリ名
   ```

2. **サイト用ファイルを用意**  
   例：index.html, style.css, README.md など

3. **Gitリポジトリを初期化**

   ```sh
   git init
   ```

4. **変更をステージング**

   ```sh
   git add .
   ```

5. **コミット**

   ```sh
   git commit -m "初回コミット"
   ```

6. **GitHubで新しいリポジトリを作成**  
   例：https://github.com/ユーザー名/リポジトリ名.git

7. **リモートリポジトリを登録**

   ```sh
   git remote add origin https://github.com/ユーザー名/リポジトリ名.git
   ```

8. **プッシュ**

   ```sh
   git push -u origin main
   ```

9. **GitHub Pagesの公開設定**
   - GitHubリポジトリページで「Settings」→「Pages」
   - 「Branch」で main を選択し「Save」

10. **公開URLで確認**  
     数分後、  
     `https://ユーザー名.github.io/リポジトリ名/`  
     でサイトが公開されます

---

> ※このREADME.mdは、既存ディレクトリからGitHub Pages公開までの手順をまとめたものです。  
> 必要に応じて内容を編集してご利用ください。
