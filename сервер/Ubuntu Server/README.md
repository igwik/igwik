Ubuntu Server   26.04.2026

Действия после установки

Сразу после установки Ubuntu Server 22.04 я выполняют ряд минимальный действий и настроек:
1. Актуализирую доступные пакеты в репозиториях:
sudo apt update
2. Устанавливаю доступные обновления для системы:
sudo apt upgrade
3. Устанавливаю нужную мне временную зону:
sudo timedatectl set-timezone Asia/Barnaul
Посмотреть перечень доступные временных зон можно вот такой командой:
sudo timedatectl list-timezones
4. Указываю FQDN имя хоста:
sudo hostnamectl set-hostname ubuntu.itproblog.ru
Это самый минимум настроек, который я выполняю после установки Ubuntu Server.

LVM Snapsots Создание снапшота (Точка восстановления) 


openssl req -x509 -out igwik.ru.crt -keyout igwik.ru.key \
  -newkey rsa:2048 -nodes -sha256 \
  -subj '/CN=igwik.ru' -extensions EXT -config <( \
   printf "[dn]\nCN=igwik.ru\n[req]\ndistinguished_name = dn\n[EXT]\nsubjectAltName=DNS:igwik.ru\nkeyUsage=digitalSignature\nextendedKeyUsage=serverAuth")
