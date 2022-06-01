<h2 align="center"> Hi there I'm Lekksha 👋 <h2>

### I'm a C# /.NET Developer 
- 🚀 Graduated from VOENMECH with a degree in Instrumentation of Spacecraft
- 💪 Graduated from DevEducation IT-college with a degree of back-end development
- 🌍 I speak Russian (native), English (B2)
- 🥅 Currently learning C#, SQL and Javascript
- 📫 Telegram: https://t.me/alevsey

## Languages and Tools:
![C#](https://img.shields.io/badge/-C%23-green?style=for-the-badge&logo=appveyor)
![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white) 
![RabbitMQ](https://img.shields.io/badge/Rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) 
![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white) 
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white)
![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Sever-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white) 
---
## Stats:
![](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=AzarovRoman&theme=solarized_dark)
![](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=AzarovRoman&theme=solarized_dark)
---

Мои проекты:
1) https://github.com/Lekksha23/MarvelousService

Микро-сервис, занимающийся оформлением подписок на услуги.
Используется Dapper для общения с базой данных, реализован паттерн MVC. Общение с другими микро-сервисами через RestSharp или RabbitMQ с MassTransit. Подключено логгирование. Аутентификация и авторизация через сторонний сервис Аутентификации.
Все возможные сценарии протестированы с помощью NUnit и Moq (Покрытие 70%).

2) https://github.com/ValeraPo/CleanMOQasine

Backend для сайта компании, занимающейся клинингом.
Используется DI (Подключен самостоятельно). Entity Framework. Аутентификация с помощью JWT-токена. Реализован паттерн MVC. Авторизация осуществлена для разных ролей. Все возможные ошибки обрабатываются на middleware.
Код протестирован с помощью библиотеки Moq и NUnit.

3) https://github.com/Arctic-beaver/KoCowork

WPF приложение для системы коворкинга.
Можно забронировать себе место, заказать продукты (снеки, воду).
Реализован паттерн MVVM. Для работы с базой данных использован Dapper и Linq. Код тестировался через NUnit.

4) Имею опыт работы с сервисами:
- CRM (у нас было более 4 млн записей в БД)
- TransactionStore (было более 42 млн)
- Сервис репортинга (содержащий информацию обо всех БД и выдающий интересную информацию об этих БД)
- RatesApi (сервис, выдающий курсы валют)
- Сервис обновления ролей лидов
- Сервис настроек, которые нужны другим сервисам
- Сервис Аутентификации. (Через этот сервис наши сервисы получали Jwt токены для лидов и токены для общения между микросервисами)