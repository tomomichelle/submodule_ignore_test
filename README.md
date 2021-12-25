# submodule_ignore_test

サブモジュールに関する知見メモ

サブモジュールを登録した時点でサブモジュールはStage上に上がるのでignoreに書いても意味ない

だからといって, `git rm` すると`git clone --recursive` してもサブモジュールがCloneされない

サブモジュールをPrivateにするのが得策.

サブモジュールがPrivateの場合, リリースにはサブモジュールのフォルダのみが用意され, 中身はからになる. これは親レポジトリがPrivateの場合でも同様.
