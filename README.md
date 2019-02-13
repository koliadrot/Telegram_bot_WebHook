EN:

Telegram Bot with Webhook

The main task of this bot, to respond to user requests, about the current price of a certain cryptocurrency.
Also, there are additional functions for convenient operation via the Telegram messenger, such as: send
messages to the mailbox directly through the chat channel telegram.

This bot works as follows: The bot accepts the request from the Server Telegrams and the bot processing 
the data sends the data to the server.

This method is effective compared to the reverse method of Webhook (the bot itself requests(spam) telegrams 
server,and the telegram server responds to it), since the delay between the bot and the server almost 
disappears and the unsatisfactory results that could pass between requests disappear.

Useful notes to get started:
1. Don't forget to insert your Telegram token in the data_api_bot file - the variable "token"
2. For correct operation of the function of sending messages, you need to register on
   Sendgrid website (https://sendgrid.com/pricing/), choose the free version by following
   instructions on the site to get your Sendgrid token, when you need to insert it in the file
   data_api_bot - the variable "token_sg" and write the name of the sender in the send_email file
   variable "from_email". Do not forget when creating a token on the Sendgrid website, give
   your token has all the authority when working with a message so that there are no problems with the rights.
3. The bot was placed on the site of the service - https://www.pythonanywhere.com
   The cost of the service is free, you only need to renew it every 3 months, this too
   is free!

Details on the methods Telegram bot look at - https://core.telegram.org/bots/api

RU: 

Телеграмм Бот с Webhook 

Главная задача этого бота, отвечать на запросы пользователей, об актуальной цене определенной криптовалюты. 
Так же, есть дополнительные функции для удобной работы через мессенджер Телеграм, такие как:отправлять 
сообщения на почтовый ящик непосредственно через сам чат телеграм-канала. 

Данный бот работает по следующему принципу: Бот принимает запрос от Телеграмм сервера и бот обрабатывая дан- 
ные, отправляет данные серверу. 

Данный метод эффективен по сравнению с методом обратному Webhook(Бот сам запрашивает(спамит) телеграмм сервер, 
а телеграмм сервер ему отвечает), так как задержка между ботом и сервером практически исчезает и пропадают не- 
удовлетворительные результаты, которые могли проходить между запросами. 

Полезные заметки для начала работы: 
1.Не забудьте вставить ваш токен Телеграмма в файле data_api_bot - переменная "token" 
2.Для исправной работы функции отправления сообщений, нужно зарегистрироваться на 
сайте Sendgrid(https://sendgrid.com/pricing/),выбрать бесплатную версию, следуя 
инструкциям на сайте получить ваш токен Sendgrid,гда надо будет вставить в файле 
data_api_bot - переменная "token_sg" и написать имя отправителя в файле send_email 
переменная "from_email". Не забудьте при создании токена на сайте Sendgrid, дать 
вашу токену все уполномочия при работе с сообщения, чтобы небыло проблем с правами. 
3.Сам бот размещался на сайте сервиса - https://www.pythonanywhere.com 
Стоимость услуги бесплатная, нужно только каждые 3 месяца продливать, это тоже 
бесплатно! 

Подробно о методах Телеграмм бота смотреть на - https://core.telegram.org/bots/api

