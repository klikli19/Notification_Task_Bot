![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Git](https://img.shields.io/badge/git%20-%23F05033.svg?&style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
<h1 align="center">Телеграм-бот для планирования задач</h1>

<h2>Для пользователей доступны следующие функции:</h2>
<ul>
  <li>Бот позволяет вносить задачи</li>
  <li>В указанное время бот напомнит о задаче.</li>
</ul>

 **Для запуска нужно:**
1. Клонировать проект в среду разработки</li>
2. Найти в Telegram [@BotFather](https://t.me/BotFather) и запустить.
4. Ввести команду ```/newbot```  и следовать дальнейшим инструкциям для получения Token.
5. Настроить БД и прописать значения в файле **[application.properties](src/main/resources/application.properties)**, туда же записываем значение Token.
6. Запустить метод **main** в файле **[TelegramBot2Application.java](src/main/java/pro/skypro/telegrambot2/TelegramBot2Application.java)**.
7. Открыть в Telegram свою версию бота и ввести команду ```/start```.
