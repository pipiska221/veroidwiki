# Настройка Velocity

Пункты которые должны быть выполнены до прочтения остальных пунктов:\
1 - У вас должно быть 2 сервера&#x20;

{% hint style="danger" %}
Оба сервера (Velocity и purpur) должны стоять на одной ноде для стабильности соединения!
{% endhint %}

2 - Основной сервер должен быть на ядре [Paper](https://papermc.io/downloads/paper) / [Purpur](https://purpurmc.org/downloads)

## 1 - Скачивание и установка ядра Velocity

Шаг 1: Заходим на официальный сайт [Velocity](https://papermc.io/downloads/velocity) и нажимаем на синюю кнопку.

<figure><img src="https://github.com/Dosto4ka/VWIKI/assets/57598008/d38e07f4-03fe-4db8-a568-22bf1f4598a4" alt=""><figcaption></figcaption></figure>

\
Шаг 2: Зайдите на наш [сайт](https://mgr.veroid.net/), выберите сервер где у вас при создании сервера было поставлено Velocity и перейдите на него.&#x20;

<figure><img src="https://github.com/Dosto4ka/VWIKI/assets/57598008/efc57463-0c9d-4136-b2a7-01ff24f7d6b7" alt=""><figcaption><p>Выберите сервер на котором будет Velocity</p></figcaption></figure>

Шаг 2.1: Перейдите во вкладку `Файлы`

<figure><img src="https://github.com/Dosto4ka/VWIKI/assets/57598008/db428d64-da71-41d8-b1ab-be619a4a1e1f" alt=""><figcaption><p>Перейдите во вкладку <code>Файлы</code></p></figcaption></figure>

Шаг 2.2: Пролистните чуть ниже и найдите файл server.jar

<figure><img src="https://github.com/Dosto4ka/VWIKI/assets/57598008/2a01dff9-201b-433c-b9e3-fe3602f50390" alt=""><figcaption><p>Найдите предустановленый server.jar и удалите его</p></figcaption></figure>

Шаг 3: Нажмите ![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/6fb17057-ca83-4f60-b5e9-49dd7ebc379c) и удалите данный файл.

{% hint style="info" %}
1.  Находим ![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/6fb17057-ca83-4f60-b5e9-49dd7ebc379c) справа от файла\


    <figure><img src="https://github.com/Dosto4ka/VWIKI/assets/57598008/7ca41560-d5a2-4750-a177-37b062e54b34" alt=""><figcaption></figcaption></figure>
2. Выбираем в открывшемся окне `Удалить`\
   ![image](https://github.com/Dosto4ka/VWIKI/assets/57598008/b89c9910-c009-4231-8a1f-2939698177dd)
{% endhint %}

Шаг 4: Заходим в загрузки браузера и переносим файл с ядром который недавно скачали в область где находятся другие файлы.

<figure><img src="https://github.com/Dosto4ka/VWIKI/assets/57598008/089a87f1-34f9-47df-bcfa-00bbe1a80b32" alt=""><figcaption></figcaption></figure>

Шаг 5: Скопируйте имя файла.

Шаг 6: Перейдите во вкладку `Параметры запуска`

<figure><img src="https://github.com/Dosto4ka/VWIKI/assets/57598008/3857f6df-5660-4bba-a7b8-6743866e613e" alt=""><figcaption></figcaption></figure>

Шаг 6.1: Нажмите на версию вашей Java.&#x20;

<figure><img src="https://github.com/Dosto4ka/VWIKI/assets/57598008/20251b27-8159-4bd1-8f93-22f14fc76668" alt=""><figcaption><p>Измените Java и имя ядра</p></figcaption></figure>

Шаг 6.1.1: Выберите значение `Java 16` или `Java 17`

<figure><img src="https://github.com/Dosto4ka/VWIKI/assets/57598008/8ef6475f-eb66-4fe7-ae23-6a8ad06a83c2" alt=""><figcaption><p>Выберите Java</p></figcaption></figure>

Шаг 6.2: Вставьте ранее скопированное имя файла в раздел `ИМЯ ЯДРА У СЕРВЕРА`

Шаг 7: Запустите сервер Velocity используя вкладку `Консоль`&#x20;

<figure><img src="https://github.com/Dosto4ka/VWIKI/assets/57598008/24d55d10-ee7d-43d6-9955-b4ab22cc7006" alt=""><figcaption></figcaption></figure>

## 2 - Настройка Velocity

Шаг 1: Перейдите во вкладку `Файлы`&#x20;

<figure><img src="https://github.com/Dosto4ka/VWIKI/assets/57598008/db428d64-da71-41d8-b1ab-be619a4a1e1f" alt=""><figcaption></figcaption></figure>

Шаг 2: Найдите файл с названием `Velocity.toml`

<figure><img src="https://github.com/Dosto4ka/VWIKI/assets/57598008/93545e21-f4a3-4290-8099-021444e04204" alt=""><figcaption><p>Файл</p></figcaption></figure>

Шаг 3: Просмотрите файл и найдите 16 строку\
Шаг 3.1: Измените значение online-mode с `true` на `false`.

<figure><img src="https://github.com/Dosto4ka/VWIKI/assets/57598008/081ca7d2-1887-40a0-9980-1aba43d67701" alt=""><figcaption><p>Строка</p></figcaption></figure>

Шаг 4: Найдите 37 строку

<figure><img src="https://github.com/Dosto4ka/VWIKI/assets/57598008/58f0d09d-ccc6-426f-8bc1-f52cd13a6c30" alt=""><figcaption><p>Способ защиты между серверами</p></figcaption></figure>

Шаг 4.1: Измените значение player-info-forwarding-mode с `NONE` на `modern`.

Шаг 5: Найдите 75 строку

<figure><img src="https://github.com/Dosto4ka/VWIKI/assets/57598008/a6e0dc28-d6a5-48a4-93f9-d4a6ed74a203" alt=""><figcaption><p>Настройка сервера</p></figcaption></figure>

Шаг 5.1: Измените значение `127.0.0.1:30066` на `172.18.0.1:port` в изменённом варианте нужно сменить port на порт вашего основного сервера и у вас есть возможность изменить название `lobby` на то которое вам нужно.

Шаг 6: Найдите 81 строку

<figure><img src="https://github.com/Dosto4ka/VWIKI/assets/57598008/ae1ffc17-40b0-4802-abf6-e85c6ea8d5c6" alt=""><figcaption><p>К какому профилю сервера будут пытаться подключится в первую очередь</p></figcaption></figure>

Шаг 6.1: Измените значение `lobby` на то имя которое вы поставили в шаге 5.1

Шаг 7: Найдите файл с названием `forwarding.secret` и скопируйте то что в нём находится, оно вам понадобится в пункте 3.

Шаг 8: Перезапустите сервер Velocity используя вкладку `Консоль`&#x20;

<figure><img src="https://github.com/Dosto4ka/VWIKI/assets/57598008/24d55d10-ee7d-43d6-9955-b4ab22cc7006" alt=""><figcaption></figcaption></figure>

## Категория 3 - Настройка Paper / Purpur

Шаг 1: Находим с левой стороны `Мои сервера`

<figure><img src="https://github.com/Dosto4ka/VWIKI/assets/57598008/06b65aa6-f472-4c80-8317-2528ef9c22b5" alt=""><figcaption><p>Раздел панели</p></figcaption></figure>

Шаг 1.1: Выберите ваш основной сервер и перейдите на него.&#x20;

<figure><img src="https://github.com/Dosto4ka/VWIKI/assets/57598008/efc57463-0c9d-4136-b2a7-01ff24f7d6b7" alt=""><figcaption><p>Основной сервер</p></figcaption></figure>

Шаг 2: Перейдите во вкладку `Файлы`&#x20;

<figure><img src="https://github.com/Dosto4ka/VWIKI/assets/57598008/db428d64-da71-41d8-b1ab-be619a4a1e1f" alt=""><figcaption><p>Вкладка файлы</p></figcaption></figure>

Шаг 3: Пролистните чуть ниже и найдите файл `paper.yml`

Шаг 4: Найдите в данном файле категорию `velocity-support`

<figure><img src="https://github.com/Dosto4ka/VWIKI/assets/57598008/d59f3936-2a98-448f-ac41-aca597de5c2c" alt=""><figcaption><p>Конфигурация Velocity в paper и его форках</p></figcaption></figure>

Шаг 4.1: Измените значение enabled с `false` на `true`.\
Шаг 4.2: Измените значение secret на то что вы скопировали. (2 пункт, шаг 7)

Шаг 5: Перезапустите оба сервера.

## Небольшая заметка:

Подключаться нужно через Velocity. **Напрямую подключиться к указанному в конфигурации серверу не получиться!** В случае если остались вопросы или данная статья вам не помогла, обратитесь в тикеты.&#x20;
