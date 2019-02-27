## Простой веб сервер на Elixir для замера производительности на выдачу ответа для GET запроса. 

**Настройка и запуск сервера:**
1. mix deps.get
2. iex -S mix
3. Установить wrk - https://github.com/wg/wrk/wiki/Installing-wrk-on-Linux
4. wrk -d30s -t10 -c5000 http://localhost:4004/hello
