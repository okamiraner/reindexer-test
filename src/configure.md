# Запуск сервера

Запустите исполняемый файл `reindexer_server` c root-правами:

```sh
sudo /opt/homebrew/bin/reindexer_server -d --pidfile=/private/var/run/reindexer/reindexer_server.pid
```

По умолчанию web-интерфейс будет доступен по адресу
[http://0.0.0.0:9088](http://0.0.0.0:9088).

Консольная утилита `reindexer_tool` взаимодествует с сервером
через gRPC по адресу [cproto://0.0.0.0:6534](cproto://0.0.0.0:6534).
