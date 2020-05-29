# eikan9_2018_player_management_tool
パワプロ2018 栄冠ナイン 選手管理ツール

## history

```
# vue.js環境構築
npm install -g @vue/cli
vue --version
# @vue/cli 4.4.1
vue create frontend
cd frontend
npm run serve
# http://localhost:8080/にアクセスして確認
# Python環境構築
conda create -n eikan9 pip
conda activate
pip install flask flake8 flask-sqlalchemy
mkdir backend
```

```
# 動作確認
cd frontend
vue run build
cd ../backend
python app.py
```