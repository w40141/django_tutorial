# django_tutorial

[Djangoのチュートリアル](https://docs.djangoproject.com/ja/3.0/intro/tutorial01/)
によるアプリの覚書.  
環境は
- python 3.8.2
- django 3.0.6
- poetry 0.1.0

---
1. 環境設定.

        mkdir path/to/project_name
        cd path/to/project_name

1. pythonのバージョン設定（必要なら）.

        pyenv local version
        pyenv rehash

1. poetryで仮想環境を作る.

        poetry init
        # djangoを入れる
        poetry install
        poetry shell

1. djangoでprojectを作る.

        django-admin startproject project_name
