# streamlit_covid19
- covid19に関するオープンデータを題材にした可視化アプリのトレーニングです。
- 政府提供のオープンデータのリンクを直接読み込んで最新のデータフレームを作成します。
- 都道府県を選択してplotlyで可視化、また新規陽性者数を日本地図上にも可視化します。
- Dockerにて、streamlitとjupyter notebook環境を構築します。


```
リポジトリに移動して
docker compose up
```

正常に動作したらブラウザで下記のURLを入力
```
可視化アプリの起動
http://localhost:8501/
```
```
Jupyter notebookの起動
http://localhost:8888/
```
