1. Вставляем в текстовый файл usernames.txt ники селебрити за которыми хотим следить

2. Заходим в settings.py и настраиваем каждую опцию под себя
    • PROXY — тут указываем прокси в формате "scheme://username:password@ip:port" или оставляем как есть, если прокси не нужен
    • MAX_RETRIES — сколько раз будем траить, если запрос к X API зафейлится
    • CHECK_RETWEETS — False или True, должен ли скрипт проверять ретвиты или только оригинальные твиты (приводит к увеличению количества запросов к API)
    • PARSING_INTERVAL_MINUTES — пишем сколько минут ждать перед началом следующего парсинга всех аккаунтов
    • BEARER_TOKEN — токен, полученный с X Developer Portal (гайд будет в комментах  💬)
    • TELEGRAM_BOT_TOKEN — токен бота в телеграм (создать бота можно через @BotFather)
    • TELEGRAM_CHAT_ID — чат id куда отсылать найденный контракт (получить id можешь у @getmyid_bot)
