# Junior Frontend + QA: **Тестирование логина и отправки рассылки [АРХИВ]**

## Задача

Напишите e2e-тесты для сценариев входа в приложение и отправки произвольной рассылки.

## Когда всё готово

1. Выложите на гитхаб репозиторий с тестовым заданием
2. Создайте пулл-реквест на гитхабе со всеми файлами вашего проекта
3. Пригласите в свой репозиторий камрадов: bitoptik, nipanasovich, rosendi, alexander-litvinovich, yukonovalov, victor-magarlamov
4. Отправьте ссылку на репозиторий как отклик на вакансию в hh
5. Отправьте нам ссылку на видео, где видно, что ваши тесты у вас запустились и проходят

## Наши ожидания

Сначала мы будем смотреть, работает задание или нет, поэтому нам нужна ссылка на репозиторий, чтобы мы могли его склонировать и запустить.

Мы ждём, что в написании e2e-тестов вы:

- посмотрите продукт и познакомитесь с предметной областью
- будете использовать Cypress (https://www.cypress.io/)
- будете использовать JS ES6

При оценке задания мы обращаем внимание на следующие вещи:

- Работоспособны ли тесты — если они не запускаются, мы расстраиваемся и проверяем код с большим скепсисом
- Насколько тщательно вы подготовились: как разобрались в продукте и какие дополнительные кейсы добавили в сценарии
- Насколько тесты независимы от html-кода страницы и какие селекторы вы используете
- Как сгруппированы тестовые блоки и какие комментарии вы оставили в коде

![image](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c2a91adb-2897-4d2f-bb5b-7189d522b201/Untitled.png)

⚡️ **На автомате накидали всё в index.js?** ⚡️

*Если вы так и сделали, то мы заранее просим отрефакторить такое «выполненное» задание.*

Вы пишете код для людей. Лучше потратьте чуть больше времени, но решите задачу качественно.

## Что понадобится для задания

Зарегистрировать бесплатный аккаунт в [Sendsay](http://sendsay.ru). *Используйте промокод «**тест**» при заполнении регистрационной формы.*

Сценарий входа в приложение (обычный вход и корпоративный):
``` 
1. Я захожу на https://app.sendsay.ru/signin
2. Ввожу логин, пароль и нажимаю «Войти»
3. Если введение данные валидны, то я попадаю в приложение
4. Если введенные данные невалидны, то …
``` 
Сценарий отправки еmail-выпуска (некорпоративный аккаунт):
``` 
1. Я залогинен в приложении
2. Захожу в раздел «Рассылки» на https://app.sendsay.ru/campaigns/issues
3. Создаю новый email-выпуск
4. Я прохожу все обязательные шаги визарда формирования email-выпуска
5. Отправляю выпуск рассылки
``` 
**P.S.**

Если хотите задать вопрос по тестовому заданию, до того как откроете пулл-реквест 👉 https://t.me/joinchat/CN4mgxZRCXU-uRZo9VBuWw — Это тихий чат, задаёте вопрос и получаете ответ. На обыденные темы разговаривать запрещается. Сообщения цензурируются, болтуны банятся.

**P.P.S.**

Многие соискатели совсем не умеют читать или читают, но очень невнимательно. Если вы внимательный читатель, поместите в корне репозитория файл с названием `SimonSays.md` и внутри напишите какую-нибудь смешную фразу-палиндром на русском или английском языке.

**P.P.P.S.**

Для выполнения задания вам понадобится бесплатный аккаунт в Sendsay. Вам также очень поможет поиск по [описанию API](https://sendsay.ru/api/api.html) и [API-коннектор](https://github.com/sendsay-ru/sendsay-api-js). *(Спасибо, Кирилл 👋)*

**P.P.P.P.S.**

Мы смотрим, проверяем код и тестируем функциональность всех тестовых заданий. На проверку тестового задания, сделанного на среднем уровне (не совсем плохо, но и не восхитительно) уходит от двух дней до недели.

Восхитительно сделавшим тестовое, мы почти не пишем комменты. Сделавшим «совсем плохо» тоже стараемся отвечать побыстрее, но иногда пишем общими фразами.

Иногда мы просим доработать какие-нибудь части задания — так мы проверяем насколько  комфортно нам будет вместе работать.

### Для справки

— https://help.github.com/en/articles/creating-a-pull-request

— https://help.github.com/en/articles/requesting-a-pull-request-review