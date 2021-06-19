# AWS App Runner 公式サンプル写経

## はじめに
このリポジトリは[AWS App Runner 公式サンプル](https://docs.aws.amazon.com/ja_jp/apprunner/latest/dg/getting-started.html)
の写経です。

## ローカル環境での動かし方

### 初回

```shell
cd <本リポジトリをcloneした場所>
pip install -r requirements.txt
export env NAME=<任意の値>
python server.py
```

### 2回目以降

```shell
cd <本リポジトリをcloneした場所>
export env NAME=<任意の値>
python server.py
```

