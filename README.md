Добавить принтер
Sudo apt install cups-pdf
http://localhost:631
Добавление гостевой ОС
Sudo apt-get install virtualbox-guest-additions-iso
Установка питона
Sudo apt install python3 (python3-pip)
Установка с++
Sudo apt install build-essential
Установка java
Sudo apt install default-jdk
Установка postgresql
Sudo apt install postgresql
Проверка что сервер работает: sudo systemctl is-active postgresql
Проверка, что служба включена: sudo systemctl is-enabled postgresql
Статус БД: sudo systemctl status postgresql
Зайти в субд под супер юзером: sudo -u postgres psql
Сменить пароль: ALTER USER postgres WITH PASSWORD ‘Новый пароль’
Установка android studio
Sudo apt install defauit-jdk
Как проверить поддержку виртуализации: grep -E “svm/vms” /proc/cpuinfo
SSH
Sudo apt install openssh-server
Sudo systemctl status ssh 
Группа пользователей 
Sudo apt install gnome-system-tools
