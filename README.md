# Настройка Docker с Yii2 Advanced + PHP7.4 + HGINX + MySQL5.7 + Admine

Собрал всего с миру по нитке и получился хороший конфиг для поднятия Yii2 через Docker.

1. Скачать репозитарий: `git clone git@github.com:fedorovanton/yii2-advanced-docker.git`
2. Удалить мой .git: `rm -r .git`
3. Скачать Docker (https://docs.docker.com/desktop/) и Docker Compose (https://docs.docker.com/compose/).
4. Сделать сборку из конейнеров: `docker-compose build`
5. Запустить сборку контейнеров в фоне: `docker-compose up -d`. Для остановки и разборки: `docker-compose down`.

Интрукцию наверно буду дополнять, чтобы было понятно что и зачем использовалось.