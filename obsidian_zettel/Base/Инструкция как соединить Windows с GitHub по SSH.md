Tags: #
___
# Инструкция как соединить Windows с GitHub по SSH
1.   Не забываем сделать если не сделано [[Первоначальная настройку git]]
2.   Вызываем в cmder вкладку bash
3.   Генерация ключа SSH.
	-  `ssh-keygen -t rsa -b 4096 -C "ваша@почта.com"`
4.  Добавление SSH-ключа в ssh-agent.
	- ```eval `ssh-agent -s` ```
	- `ssh-add ~/.ssh/id_rsa`
5.  Добавление ключа SSH в учетную запись GitHub.
___
### Zero-Links
- [[00 GitHub]]
- [[00 SSH]]

___
### Links
- [Ссылка на пошаговое руководство](https://only-to-top.ru/blog/tools/2019-12-08-git-ssh-windows.html)