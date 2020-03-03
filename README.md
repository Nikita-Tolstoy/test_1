# Система переводов
## Описание проекта	

Проект представляет из себя REST API, которое позволяет  выполнять следующие действия:
- зарегистрировать пользователя с указанием
  - начальный баланс
  - валюта счета
  - email (уникальный; используется для входа)
  - пароль
- аутентифицировать пользователя по почте и паролю
- перевести средства со своего счета на счет другого пользователя (используйте [формулу конвертации](https://academy.terrasoft.ru/sites/default/files/documents/docs/product/bpm'online%20sales/team/7.7.0/BPMonlineHelp/chapter_currencies/faq_exchange_rates.htm), если валюты счетов отличаются)
- просмотреть список всех операций по своему счету
- обновлять курсы валют со стороннего ресурса (например, [exchangeratesapi.io](https://exchangeratesapi.io/)) раз в N времени (например, раз в 3 минуты)

Система должна поддерживать следующие валюты: EUR, USD, GPB, RUB, BTC
# Требования к системе
- система должна быть реализована на любом python-фреймворке на ваш выбор: Django, Flask, aiohttp, Sanic, Bottle и пр
- для хранения данных должна использоваться СУБД Postgres
- код должен запускаться в Docker-контейнерах
- код должен быть покрыт unit-тестами

# Несистемные требования
- на проект отводится 4-8 часов
- проект должен содержать README, где будет описано как запускать проект
- проект должен быть залит на GitHub/GitLab/BitBucket
- проект должен содержать осмысленные коммиты

# Как запустить проект


