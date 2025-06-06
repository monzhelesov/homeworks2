# Домашнее задание к занятию "Уязвимости и атаки на информационные системы" - Монжелесов Роман
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

2. ![alt text]()

### Задание 1

1. Сетевые службы, которые разрешены: OpenSSH, HTTP, Telnet, MySQL

2. Обнаруженные уязвимости: vsftpd 2.3.4 Backdoor Command Execution (https://www.exploit-db.com/exploits/17491), PHP-CGI Argument Injection (https://www.exploit-db.com/exploits/19233), Samba Username Map Script (https://www.exploit-db.com/exploits/16320)

### Задание 2

1. Режим SYN Отправка SYN без завершения TCP; Сервер реагирует - Ответ SYN-ACK (открыт) или RST (закрыт)

2. Режим FIN FIN-пакет без SYN; Сервер реагирует - Игнорирует (открыт) или RST (закрыт) 

3. Режим Xmas Устанавливаются флаги FIN, URG, PUSH; Сервер реагирует - Игнорирует (открыт) или RST (закрыт)

4. Режим UDP Отправляются udp пакеты, а не tcp; Сервер реагирует - Нет ответа (открыт), ICMP port unreachable (закрыт)
