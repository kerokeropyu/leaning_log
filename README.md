- 仮想環境を立ち上げる  
```ll_env\Scripts\activate```

- ジャンゴインストール  
```pip install django```

- プロジェクト作成  
```django-admin startproject learning_log .```

- バージョン確認  
```python -m django --version```

- データベースを作成する  
```python manage.py migrate```

- プロジェクトを表示する  
```python manage.py runserver```

- アプリケーションを開始する  
```python manage.py startapp learning_logs```

- マイグレーションファイルを作成する  
```python manage.py makemigrations learning_logs```

- マイグレーション実行  
```python manage.py migrate```

- スーパーユーザーを設定する
```python manage.py createsuperuser```

- usersという新しいアプリケーションを作成
```python manage.py startapp users```


- 追加文書
「チェス」
序盤とは、ゲームの開始部分で最初の10手くらいまでの局面のことを指す。序盤では三つのことを心がけるのが良い。ビショップとナイトを持ち出すこと、盤の中央を支配すること、そしてキャスリングすることである。
これらはもちろん単なる手引きに過ぎない。手引きに従うときときとそうでないときの見極めを学ぶことが重要だろう。

「ロッククライミング」
クライミングで最も大事なことの一つは、できるだけ両足で体重を支え続けることだ。クライマーは一日中両腕でぶら下がっていられるという都市伝説がある。実際の優れたクライマーは、どんな時でも可能な限り両足で体重を支え続けるための特別な方法を練習している。