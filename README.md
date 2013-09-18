xcode-library-sample
====================

開発時
------

1. library-dev で library を選択し実装ファイルを追加する。その際、追加するファイルのターゲットは library 及び library-dev を指定する。
2. 動作を確認する際は library-dev ターゲットを選択したのちにシミュレータ、実機で確認する。

ライブラリ作成、動作確認
------------------------

1. library-dev プロジェクトの build-library ターゲットを実行して <PROJECT>/build/Debug/library 以下にライブラリを作成する。
2. 作成されたライブラリを library-sample プロジェクトにコピーする。（コピー済み）
3. library-sample からライブラリのコードを実行する。
