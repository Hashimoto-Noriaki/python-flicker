### 前提
python3

### flickrapi モジュールのインストール
```
pip3 install flickrapi
```
#### インストールの確認
```
pip3 show flickrapi
```

### 仮想環境の使用 (オプション)
- 仮想環境の作成
```
python3 -m venv venv
```

- 仮想環境の有効化:
```
source venv/bin/activate
```
### 依存関係の再インストール
```
deactivate
rm -rf venv
python3 -m venv venv
source venv/bin/activate
pip install flickrapi
```
### スクリプトの実行(画像)
keyとsecretを変更

ここでは、monkey
```
cd intro_deep_learning
python3 download.py monkey
```


