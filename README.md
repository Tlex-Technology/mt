# M_bot

## English:

## Русский:

### Описание 
Бот позволяет записывать, читать, отправлять в группу/канал, и удалять сообщения полученные от пользователей, а так - же банить пользователей


### Инструкция по развертыванию
  1. Клонируйте ветку master.bot из репозитория M_bot:

  ```
    git clone https://github.com/Ah-ru/M_bot --branch master.bot
  ```

  2. Перейдите в директорию M_bot:

  ```
    cd M_bot
  ```

  3. Установите библиотеки:

  ```
    pip install -r requirements.txt
  ```

  Если у вас не получилось, попробуйте:

  ```
    pip3 install -r requirements.txt
  ```

  4. Создайте .env файл по шаблону:
    
  TGAPI = "Your Telegram_api_token" Ваш Api token telegram bot/ апи токен телеграм бота.\
  GID = "Group_ID_(integer)"        Ваш id группы / id - ай-ди.\
  NDB = "your_path_to_database"     Ваш путь к базе данных.


  **Подсказка:** Для получения пути до рабочей директорию Linux:

  ```
    pwd
  ```
  Вы получите путь по директории M_bot\
  Например : /home/test/M_bot\
  После этого добавьте в конец любой текст на английском с расширение .db\
  Например : /home/test/M_bot/tg.db - это и будет путь до базы данных

  5. После всех описанных выше шагов, запустите файл 'main.py':

  ```
    python main.py
  ```

  Если у вас не получилось, попробуйте:

  ```
    python3 main.py
  ```
  *Для остановки CTRL+C*
    
