# selenium_sample
seleniumのサンプルスクリプトとdocker設定ファイル

### PCにdockerをインストールし起動します。アカウント登録も必要です。
https://www.docker.com/

### git cloneしdockerコンテナを作成、起動します。
```
$ git clone https://github.com/takashi-yamada-f/selenium_sample.git
$ cd selenium_sample
$ docker-compose build
$ docker-compose up -d
```

### ログインし、サンプルプログラムを起動します。
```
$ docker ps
$ docker exec -it selenium_sample_python_app_1 bash
# cd /scraping
# python itell_headless.py 
.
----------------------------------------------------------------------
Ran 1 test in 24.141s

OK
```

