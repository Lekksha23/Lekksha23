<h2 align="center"> Hi there I'm Aleksey 👋 <h2>

### I'm a C# /.NET Developer 
- 🚀 Graduated from VOENMECH with a bachelor's degree in Instrumentation of Spacecraft
- 💪 Graduated from DevEducation IT-college and passed internship in XCritical company
- 🌍 I speak Russian (native), English (B2)
- 🥅 Currently learning Javascript
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

My projects:
1) https://github.com/Lekksha23/MarvelousService

A micro-service that handles subscriptions to services. I used Dapper to communicate with the database, 
the MVC pattern is implemented. Communicating with other micro-services via RestSharp or RabbitMQ with MassTransit.
Logging enabled. Authentication and authorization through a third-party Authentication service. All possible scenarios tested with NUnit and Moq (70% coverage)

2) https://github.com/ValeraPo/CleanMOQasine

Backend for a cleaning company website.
I used DI. Entity Framework Core. Authentication with a JWT token. Implemented MVC pattern.
Authorization is implemented for different roles. All possible errors are handled by the middleware.
Code tested with Moq library and NUnit

3) https://github.com/Arctic-beaver/KoCowork

WPF application for coworking system.
You can reserve a seat, order groceries (snacks, water).
Implemented MVVM pattern. Dapper and Linq were used to work with the database. The code was tested with NUnit.

4) I have experience with the following services:
- CRM (we had over 4 million records in the database)
- TransactionStore (was over 42 million records)
- Reporting service (containing information about all databases and providing interesting information about them)
- RatesApi (service that issues exchange rates)
- Service for updating lead roles
- Service settings that other services need
- Service Authentication. (Through this service, our services received Jwt tokens for leads and tokens for communication between microservices)