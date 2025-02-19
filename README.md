# How to use

0. `git clone --recurse-submodules <try_rabbitmq_pyenvリポジトリのURL>`する場合は`手順3`を省略可能。
1. `try_rabbitmq_pyenv`フォルダを`vscode`で`open`
2. `terminal`を`open`
3. `git submodule update --init --recursive`を実行
    `./app/try_rabbitmq`が更新される
4. `docker compose up -d`を実行
5. 起動した`python-dev`コンテナにvscodeをアタッチ
6. `python-dev`にアタッチしたvscodeのファイルメニューから`/app/try_rabbitmq`フォルダをopen
7. 以降は`try_rabbitmq`リポジトリの`README.md`を参照
