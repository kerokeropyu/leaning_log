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