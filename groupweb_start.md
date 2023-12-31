## Инструкция по созданию проектов (сайтов)

### Регистрация и настройка записей домена

1. Зарегистрировать домен. Можно обычный, можно перехватить освобождающийся (например через https://expired.ru/)
2. Настроить NS записи домена на какой нибудь NS хостинг, например раздел Networking у [DigitalOcean](https://m.do.co/c/94bff2ad7404). Можно использовать такую услугу у регистратора домена, или [делегировать домен на Яндекс](https://yandex.ru/support/business/domains/delegate-domain.html)
3. Настроить A запись домена на IP `176.57.211.167`
4. Подождать пока NS записи обновятся. Если домен был только делегирован, может пройти несколько часов. Как понять что все заработало: при заходе на http://ваш-домен.ru вы должны увидеть стандартную ошибку сервера что сайт не найден

### Добавление сайта в панель

1. Зайдите в панель по адресу https://groupweb.ru/nova/resources/sites
2. Нажмите кнопку `Create Site`
3. Заполнить и отправить форму, вуаля сайт готов к работе

### Добавление ключей

В списке сайтов или на странице сайта используй команду `Add Keys`

### Главная страница

Главную страницу сайта необходимо создать вручную, создав страницу с адресом `/`

### Специальные страницы

* `robots.txt` - создан автоматически, при необходимости можно изменить через файл менеджер
* `sitemap.xml` - создается / обновляется автоматически каждую ночь, если за прошедшие сутки создавались новые страницы
* Протокол IndexNow - новые страницы автоматически отправляются в Яндекс
* `pages-turbo.xml` - фид Турбо страниц для Яндекса
* `pages-feed.xml` - фид "Свежее и актуальное" для Яндекса

### Изменение и настройка шаблона

🛠️ в разработке 🛠️

### Где брать ключевики

Например сгенерить здесь https://words.groupweb.ru/
