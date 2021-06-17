# Office 製品の Git 管理例

あまり使いたくはないが、どうしても Excel 、 Word 、 PowerPoint を Git で管理する場合の例

## 必要なツール

- [java]

  OpenJDK などで `java` コマンドが実行できるようにする

- [tika]

  自分のホームディレクトリーにクローンする

  ```bash
  cd tika
  bash git-config-global.sh
  ```

  環境変数 `JAVA_TOOL_OPTIONS` に `-Dfile.encoding=utf-8` を設定する

- [git-xl]

  [インストーラー][xl-installer]をダウンロードして実行する

インストール後、コマンドプロンプトや VSCode を再起動する

## 推奨ツール

- [VSCode]

  ステージすれば変更箇所が見える（ステージしないと見えない）

  [Git History][history] の Extension を追加すれば過去の変更箇所も見える

  マクロの変更は見えない

- [Tortoise Git][tortoise]

  Office 製品を開いて差分が見える

[java]: http://jdk.java.net/
[tika]: https://github.com/lagenorhynque/tika
[git-xl]: https://github.com/xlwings/git-xl
[xl-installer]: https://github.com/xlwings/git-xl/releases/download/0.5.0/git-xl-windows-0.5.0.exe
[vscode]: https://azure.microsoft.com/ja-jp/products/visual-studio-code/
[history]: https://github.com/DonJayamanne/gitHistoryVSCode
[tortoise]: https://tortoisegit.org/
