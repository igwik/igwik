## Hi there 👋
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
<!--**igwik/igwik** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
