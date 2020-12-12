# Python環境構築手順

## インストール

```bash
apt install python3
```

## エイリアス登録

~/.zshrc の末尾に追加

```txt
alias sudo='sudo '
alias python='python3'
alias pip='pip3'
```

## Pipenvのインストール

```cmd
pip install pipenv pipenv-shebang
```

~/.zshrcの末尾に追加

```txt
export PIPENV_VENV_IN_PROJECT=true
```
