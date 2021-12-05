### Date:

2021-12-01

### Status:

Accepted

### Context:

Нам нужно определиться с реализацией нашего API Gateway. Перед нами стоит следующий выбор: 

* Рукописный модуль.
* Google Apigee.
* Google API Gateway.

### Decision:

Команда разработчиков в ходе ожесточенной дискуссии и пылкого, но мимолетного конфликта, решила что самописный модуль будет больше отвечать потребностям нашего сервиса. 

Потому что Apigee сложен в освоении и дорог, а Google API Gateway больше подходит к маппингу Google Serverless единиц наружу в интернет из внутренней сети. 

Кроме того самописаное рещение более гибко, дешево и быстрее в реализации чем готовые аналоги.  

### Consequences:

- Свой модуль приходится поддерживать чаще, на это уходят ресурсы и время. 
- Большая гибкость и отражение в себе всех ФТ/НФТ. 