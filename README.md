# 初心者向けGitチュートリアル（Git Tutorial for Beginners）
## このリポジトリについて（About This Repository）
このリポジトリは **Git/GitHub の操作を学ぶための練習用** です。  
実際の開発リポジトリではないので、自由に試しながら進めてください。

This repository is a **playground for learning fundamental Git and GitHub operations**.  
Since this is not a real development repository, feel free to experiment and practice as you proceed through the lessons.  

## 使い方（How to Use）
1. 自分の環境に **clone** してください。  
2. `lesson-01` などの教材ブランチから作業ブランチを作成してください。（下記参照） 
   ```bash
   git checkout lesson-01
   git checkout -b feature/<yourname>-lesson01
3. `index.html`などにあるコメント指示に従って編集・コミットします。 
4. 作業が終わったら`push`を行ってくささい。 
5. レッスンによっては`Pull Request`を作成してください。（PRはレビュー用です。） 

--- 

1.  **Clone** this repository to your local machine.
2.  Start from a lesson branch (e.g., `lesson-01`) and create your own dedicated working branch based on the file contents. (See example below)
    ```bash
    git checkout lesson-01
    git checkout -b feature/<yourname>-lesson01
    ```
3.  Follow the instructions commented within the files (e.g., `index.html`) to edit and commit your changes.
4.  Once your work is complete, **push** your branch to GitHub.
5.  For some lessons, you will be instructed to create a **Pull Request (PR)**. (The PR is intended for the review process.)

## 前提条件（Prerequisites）
- Git がインストールされていること
- GitHub アカウントを持っていること
- 推奨エディタ: VSCode


* Git is installed on your machine.
* You have a GitHub account.
* Recommended Editor: VSCode

## 注意事項（Important Notes）
- `develop`/`master`は教材用です。直接コミット・マージしないでください。
- 作業ブランチ名は`feature/<username>-lessonXX`の形式を推奨します。
- 間違えて操作した場合は`git reset`や`reflog`で戻すか、リポジトリ製作者に相談してください。


* The `develop` / `main` branches are for instructional purposes only. **Do not commit or merge directly to them.** (Specific instructions will be provided in Lesson 0.)
* We recommend using the branch name format: `feature/<username>-lessonXX`.
* If you make a mistake, please use `git reset` or `git reflog` to undo the operation, or consult with the repository owner.

## 参考リンク（Resources）
[GitHub Docs](https://docs.github.com/ja)
