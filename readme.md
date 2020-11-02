# Python環境構築手順

## Pythonをインストール

[公式サイト](https://www.python.org/)の「Download for Windows」からインストーラーをダウンロードして実行

インストール開始前の「Add Python 3.7 to Path」、インストール後の「Disable path length limit」を忘れないように（キャプチャ取り忘れた…）

インストール後 `python -V` でバージョンが表示されればインストール完了

## エイリアス登録

~/.bashrcの末尾に追加

```txt
alias sudo='sudo '
alias python='python3'
alias pip='pip3'
```

## Pipenvのインストール

```cmd
pip install pipenv
```

~/.profileの末尾に追加

```txt
export PIPENV_VENV_IN_PROJECT=true
```
