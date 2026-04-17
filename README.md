# Домашнее задание к занятию «Кеширование Redis/memcached» Погребенко Александр

Задание 1. Кеширование
Приведите примеры проблем, которые может решить кеширование.

Приведите ответ в свободной форме.
Ответ:
- ускорения работы сайтов и приложений;
- нижения нагрузки на серверы и БД;
- экономии ресурсов и затрат;
- улучшения SEO и UX;
- повышения устойчивости к нагрузкам.

Задание 2. Memcached
Установите и запустите memcached.
<img width="1039" height="454" alt="install mem" src="https://github.com/user-attachments/assets/756cbe53-ec8e-4e06-9f96-362e1d4e9b49" />

Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.
<img width="1021" height="190" alt="status mem" src="https://github.com/user-attachments/assets/3c15e44b-8bd1-4970-b11a-4a2682d9c2b7" />


Задание 3. Удаление по TTL в Memcached
Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5.
Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.
<img width="649" height="305" alt="key" src="https://github.com/user-attachments/assets/bd9365fe-4ac4-4be0-8672-9c2251c8b218" />

<img width="642" height="128" alt="del key" src="https://github.com/user-attachments/assets/c0711bf5-3094-482b-bd75-8410630b73ac" />



Задание 4. Запись данных в Redis
Запишите в Redis несколько ключей с любыми именами и значениями.

Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.

<img width="577" height="307" alt="redis" src="https://github.com/user-attachments/assets/b3da26f6-5261-447e-b46b-579bd56994d2" />
