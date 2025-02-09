# Домашнее задание к занятию «Кеширование Redis/memcached» Бондарев Олег

### Инструкция по выполнению домашнего задания

1. Сделайте fork [репозитория c шаблоном решения](https://github.com/netology-code/sys-pattern-homework) к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/gitlab-hw или https://github.com/имя-вашего-репозитория/8-03-hw).
2. Выполните клонирование этого репозитория к себе на ПК с помощью команды `git clone`.
3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
   - впишите вверху название занятия и ваши фамилию и имя;
   - в каждом задании добавьте решение в требуемом виде: текст/код/скриншоты/ссылка;
   - для корректного добавления скриншотов воспользуйтесь инструкцией [«Как вставить скриншот в шаблон с решением»](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md);
   - при оформлении используйте возможности языка разметки md. Коротко об этом можно посмотреть в [инструкции по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md).
4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`).
5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
6. Любые вопросы задавайте в чате учебной группы и/или в разделе «Вопросы по заданию» в личном кабинете.

Желаем успехов в выполнении домашнего задания.

---

### Задание 1. Кеширование 

Приведите примеры проблем, которые может решить кеширование. 

1. Повышение производительности
2. Увеличение скорости ответа
3. Экономия ресурсов
4. Сглаживание бустов трафика

---

### Задание 2. Memcached

Установите и запустите memcached.

Команда: sudo apt update && sudo apt install memcached

![image](https://github.com/user-attachments/assets/eb3a2593-d8d3-477e-aca4-922b7988c0fa)
![image](https://github.com/user-attachments/assets/13a37599-9c93-48de-84d6-2d7fffac52a8)

---

### Задание 3. Удаление по TTL в Memcached

Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5. 

![image](https://github.com/user-attachments/assets/e01cf9d6-63f6-4f6d-b501-bc9b1b6202a3)


---

### Задание 4. Запись данных в Redis

Запишите в Redis несколько ключей с любыми именами и значениями. 

Уставновка и проверка:
1. sudo apt install -y redis
2. sudo systemctl status redis

![image](https://github.com/user-attachments/assets/f0975996-9e7c-410e-980e-271744db7605)
![image](https://github.com/user-attachments/assets/0f7687b4-8b5c-4b68-8e6e-fe9a4642b1b0)
![image](https://github.com/user-attachments/assets/61b78a3a-be69-4f28-b7de-c01588ff88bc)


