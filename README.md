## 🚀 Warpcast adspower farm
Нахуй я этим делюсь? Этот скрипт поможет сэкономить бешеное количество времени. Он работает с профилями Warpcast, которые импортированны в [AdsPower](https://share.adspower.net/Btc9YYgpiyJxhmW). Заебался с рандомизацией, так что можешь спать спокойно.

<i>Связь с создателем: https://t.me/CrytoBusher</i> <br>
<i>Если ты больше по Твиттеру: https://twitter.com/CryptoBusher</i> <br>

<i>Залетай сюда, чтоб не пропускать дропы подобных скриптов: https://t.me/CryptoKiddiesClub</i> <br>
<i>И сюда, чтоб общаться с крутыми ребятами: https://t.me/CryptoKiddiesChat</i> <br>

## ⚙️ Функции
1. Постинг кастов на своей стене
2. Подписка на рандомных юзеров из рекомендаций (скроллит и подписывается)
3. Подписка на рандомные каналы из рекомендаций (скроллит и подписывается)
4. Серфинг ленты, включая:
   1. Скролл ленты
   2. Лайк рандомного каста
   3. Рекаст рандомного каста
   4. Букмарк рандомного каста
5. Использование поиска и последующая (со скроллом и без):
   1. Рандомная подписка на авторов постов из результатов поиска
   2. Рандомная подписка на каналы из результатов поиска 
   3. Рандомная подписка на юзеров из результатов поиска

## 🤔 Преимущества
1. Максимально - возможная рандомизация действий:
   1. Рандомизация последовательности выполнения модулей
   2. Рандомизация активностей в рамках модуля (количество interactions, скорость выполнения действий)
   3. Рандомизация основанна на вероятностях
   4. Рандомизация координат, по которым производится клик по кнопке
   5. Рандомизация задержек при вводе текста
   6. Рандомизация скролла ленты, настройки скролла
2. Работа через AdsPower
3. Headless mode
4. Возможность работать с уже открытыми профилями AdsPower
5. Использования меню Emoji при касте

## 📚 Первый запуск
1. Устанавливаем Python (я работал на 3.12).
2. Скачиваем проект, в терминале, находясь в папке проекта, вписываем команду "pip install -r requirements.txt" для установки всех зависимостей.
3. Открываем файл "data/profile_ids.py" и забиваем свои профиля как в примере ("название":"ID из AdsPower"). Название должно мэтчиться с названиями в файле "data/casts.txt". Проще всего пронумеровать, как в примере.
4. Открываем файл "data/config.py" и забиваем настройки, описания даны в самом файле. Можно написать в наш [чат](https://t.me/CryptoKiddiesChat) для уточнения каких - либо моментов.
5. Открываем файл "data/casts.txt" и вбиваем текста для постов, каждый с новой строки в формате "acc_name|cast_text". Для каждого аккаунта надо предоставлять свои текста для постов, можно вбивать много текстов для одного аккаунта, скрипт будет выбирать рандомно текста для акка или по - порядку, в зависимости от настроек.
6. Открываем файл "data/emoji_names.txt" и вбиваем туда названия emoji, по которым будет производиться поиск в контекстном меню, если в настройках вы активировали данную функцию.
7. Открываем файл "data/search_authors.txt" и вбиваем туда строки, по которым будет происходить поиск постов для последующей подписки на их авторов.
8. Открываем файл "data/search_channels.txt" и вбиваем туда строки, по которым будет происходить поиск каналов для последующей подписки на них.
9. Открываем файл "data/search_users.txt" и вбиваем туда строки, по которым будет происходить поиск юзеров для последующей подписки них.
10. Запускаем AdsPower и логинимся в свой аккаунт
11. В терминале, находясь в папке проекта, вписываем команду "python3 farm_warpcast.py" и жмем ENTER

## 🌵 Дополнительная информация
- Я не несу ответственность за ваши аккаунты (ban, shadowban). Однако данный подход был оттестирован комьюнити на примере Twitter, в данном исполнении я учел все возможные косяки, доработал некоторые алгоритмы.
- Если нашли баги - буду благодарен за обратную связь.

## 💴 Донат
Если хочешь поддержать мой канал - можешь мне задонатить, все средства пойдут на развитие сообщества.
<b>0x77777777323736d17883eac36d822d578d0ecc80<b>
