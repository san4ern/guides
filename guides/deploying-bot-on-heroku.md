---
description: >-
  » В данном гайде я подробно расскажу, как установить дискорд бота на Heroku со
  всеми особенностями
---

# Установка бота на хероку

### Пункт 1

{% hint style="warning" %}
В нашей директории бота необходимо создать файл с названием Procfile и написать там `app: node .` в случае, если наш бот написан на node.js. В противном случае - в зависимости от вашего языка программирования
{% endhint %}

> Заходим на  [https://heroku.com](https://heroku.com) и регистрируем аккаунт нажав кнопку справа вверху

![](../.gitbook/assets/izobrazhenie_2021-07-16_121450.png)

{% hint style="info" %}
После регистрации в аккаунте можно привязать карту, чтобы лимит часов в месяц был 1000, заместо 400
{% endhint %}

### Пункт 2

> Авторизуемся на [https://github.com](https://github.com) и потом скачиваем GitHub Desktop \([https://desktop.github.com](https://desktop.github.com)\)
>
> Авторизуемся в приложении и жмём эту кнопку

![](../.gitbook/assets/izobrazhenie_2021-07-16_122152.png)

![](../.gitbook/assets/izobrazhenie_2021-07-16_122213.png)

> Указываем своё название и путь к файлам и по желанию делаем публичным, либо закрытым
>
>   
> Далее делаем коммит и пушим наши файлы

### Пункт 3

> Возвращаемся на Heroku и справа вверху, ниже от аватара, жмём следующие кнопки

![](../.gitbook/assets/izobrazhenie_2021-07-16_122536.png)

> Указываем название и регион

{% hint style="warning" %}
В случае дискорд-бота, желательно указывать регион Америка, чтобы задержка была ниже
{% endhint %}

{% hint style="info" %}
Ниже мы наблюдаем эту кнопку, что-же она значит?
{% endhint %}

![](../.gitbook/assets/image.png)

{% hint style="success" %}
Данная кнопка создана для связки несколько приложений в один общий проект. В нашем случае, она особо не нужна
{% endhint %}

### Пункт 4

> Заходим в созданное нами приложение и жмём кнопку Deploy, выбираем метод публикации GitHub

![](../.gitbook/assets/izobrazhenie_2021-07-16_123228.png)

> Ниже подключаем наш GitHub-аккаунт и выбираем репозиторий для публикации

![](../.gitbook/assets/izobrazhenie_2021-07-16_123339.png)

> Ниже по желанию можно включить автоматическую публикацию, которая будет публиковать код при любом изменении в репозитории

![](../.gitbook/assets/izobrazhenie_2021-07-16_123439.png)

> Спускаемся ниже и жмём кнопку

![](../.gitbook/assets/izobrazhenie_2021-07-16_123527.png)

> У нас запускается публикация проекта и его сборка. Если результат позитивный, у нас будет примерно такой результат

![](../.gitbook/assets/izobrazhenie_2021-07-16_123645.png)

### Пункт 5

> Идём во вкладку Resources и на нашем `app: node .` жмём карандаш и нажимаем ползунок \(в моём случае `worker: npm start`\)

![](../.gitbook/assets/izobrazhenie_2021-07-16_123813.png)

> Справа жмём следующие кнопки и наблюдаем наши логи консоли \(если таковые являются\)

![](../.gitbook/assets/izobrazhenie_2021-07-16_123901.png)

![](../.gitbook/assets/izobrazhenie_2021-07-16_123918.png)

### Окончание

{% hint style="success" %}
Если тебе помог и понравился данный гайд - оставляй оценку ниже. Так-же заглядывай сюда в случае новых гайдов. Удачи!
{% endhint %}

#### 


