## Домашнее задание к занятию «Кеширование Redis/memcached» (Щербатых А.Е.)
### Задание 1. Кеширование
Приведите примеры проблем, которые может решить кеширование.
### Ответ
1. Повышение производительности.
2. Увеличение скорости ответа.
3. Экономия ресурсов. Например, время.
4. Снижение нагрузки на базу данных.
5. Сглаживание бустов трафика.

### Задание 2. Memcached
Установите и запустите memcached.

Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.
![alt text](Pictures/Picture_2.jpg)

### Задание 3. Удаление по TTL в Memcached
Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5.

Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.
![alt text](Pictures/Picture_3.jpg)

### Задание 4. Запись данных в Redis
Запишите в Redis несколько ключей с любыми именами и значениями.

Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.
![alt text](Pictures/Picture_4.jpg)

### Задание 5*. Работа с числами
Запишите в Redis ключ key5 со значением типа "int" равным числу 5. Увеличьте его на 5, чтобы в итоге в значении лежало число 10.

Приведите скриншот, где будут проделаны все операции и будет видно, что значение key5 стало равно 10.
![alt text](Pictures/Picture_5.jpg)
