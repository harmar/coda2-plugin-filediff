**coda2-plugin-filediff** - A [diff](http://github.com/harmar/coda2-plugin-filediff) plugin for [Coda2](http://www.panic.com/coda)
===

必要条件
---

 * Coda 2

インストール
---

 *  githubからダウンロード
 *  ファイルを実行 `diff.codaplugin`

アンインストール
---

 * ディレクトリを削除 `~/Library/Application Support/Coda2/Plug-ins/diff.codaplugin`

使用方法
---

### 「環境設定」 CTRL+ALT+CMD+S
### （設定ファイルを設定していない場合は、デフォルト値が適用されます。）
 * [設定ファイルを開く]
 * [DIFF]に差分を取るアプリケーションを指定（デフォルト: diff）
 * [DIFF_OPT]に上記アプリケーションのオプションを指定（デフォルト: -Naur）

### 「ファイルの差分を取る」 CTRL+ALT+CMD+A
 * 差分を取るファイルを開いた状態で、[ファイル追加]を選択（元ファイル）
 * 再度、差分を取るファイルを開いた状態で、[ファイル追加]を選択（新ファイル）
 * 環境設定で設定した差分抽出用アプリケーションで差分が表示されます。

### 「差分ファイルをクリア」 CTRL+ALT+CMD+C
 * 上記「ファイルの差分を取る」で指定するファイルを間違えてしまった場合
 * [全てクリア]を選択
 * 選択されたファイルが全てクリアされますので、再度「ファイルの差分を取る」を実施します。

変更履歴
---

### v1.0
 * v1.0 公開
