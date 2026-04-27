    Сети

for /L %i in (1,1,254) do start /min ping -n 1 192.168.0.%i

arp -a

scp OLED_lin5_i2c.py root@192.168.0.235:/root/


	Запуск от Имени пользователя

runas /user:test msedge

runas /user:test chrome
