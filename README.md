# pracmin_docker_task6.1_bonus
bonus task

Давайте кешировать запросы, для этого нам понадобится кеш (ваш К.О.). Возьмите что-нибудь популярное, например Redis.

Теперь ваш сервер из задания 6.3 должен кешировать все запросы и если запрос был ранее то отвечать Cached: ${запрос}. Напишите docker-compose.yaml где вы опишите ваш кеш, сервер, сеть и т.д.

Пример

```
$docker-compose up


$telnet localhost ${PORT}
Trying ::1...
Connected to localhost.
Escape character is '^]'.
Hello
OK:Hello
Hello
Cached: Hello
Bye
OK:Bye
```
