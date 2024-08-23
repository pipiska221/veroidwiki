---
description: >-
  Сейчас мы с вами за несколько шагов настроим geysermc. Статья сделана
  совместно с LoneWo
icon: gear
---

# Настройка Geyser

{% hint style="info" %}
Советую воспользоваться [конфигуратором ](https://geysermc.org/utilities/config\_editor)от Geyser, так вы сможете перевести функции с помощью перевода страницы, а также будете понимать что и где проще.
{% endhint %}

### 1. Скачиваем Geysermc и Floodgate.&#x20;

Ниже приведены ссылки на последнюю версию скачивания Geysermc и floodgate.&#x20;

<table><thead><tr><th width="380">Тип сервера</th><th>Geyser плагин</th><th>Floodgate</th></tr></thead><tbody><tr><td>Spigot | Paper | Purpur и остальные их форки</td><td><a href="https://download.geysermc.org/v2/projects/geyser/versions/latest/builds/latest/downloads/spigot">Скачать</a></td><td><a href="https://download.geysermc.org/v2/projects/floodgate/versions/latest/builds/latest/downloads/spigot">Скачать</a></td></tr><tr><td>Bungeecord</td><td><a href="https://download.geysermc.org/v2/projects/geyser/versions/latest/builds/latest/downloads/bungeecord">Скачать</a></td><td><a href="https://download.geysermc.org/v2/projects/floodgate/versions/latest/builds/latest/downloads/bungee">Скачать</a></td></tr><tr><td>Fabric</td><td><a href="https://download.geysermc.org/v2/projects/geyser/versions/latest/builds/latest/downloads/fabric">Скачать</a></td><td><a href="https://modrinth.com/mod/floodgate">Скачать</a></td></tr><tr><td>Velocity</td><td><a href="https://download.geysermc.org/v2/projects/geyser/versions/latest/builds/latest/downloads/velocity">Скачать</a></td><td><a href="https://download.geysermc.org/v2/projects/floodgate/versions/latest/builds/latest/downloads/velocity">Скачать</a></td></tr><tr><td>Отдельный сервер (standalone)</td><td><a href="https://download.geysermc.org/v2/projects/geyser/versions/latest/builds/latest/downloads/standalone">Скачать</a></td><td>---------</td></tr><tr><td>NeoForge</td><td><a href="https://download.geysermc.org/v2/projects/geyser/versions/latest/builds/latest/downloads/neoforge">Скачать</a></td><td>---------</td></tr><tr><td>ViaProxy</td><td><a href="https://download.geysermc.org/v2/projects/geyser/versions/latest/builds/latest/downloads/viaproxy">Скачать</a></td><td>---------</td></tr></tbody></table>

{% hint style="info" %}
После скачивания обоих плагинов для вашей версии загрузите их в папку plugins вашего сервера, и перезапустите сервер для создания конфигурации.
{% endhint %}

### 2. Создание портов.

Для настройки прокси вам необходимо минимум два порта. Один будет для вашего основного сервера, второй для подключения с Bedrock издания Minecraft. Создаем порт так:&#x20;

1. Заходим во вкладку `Порты`
2. Нажимаем `Создать порт.`
3. Копируем выданный нам новый порт. У него должна отсутствовать пометка `Основной`

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption><p>Шаги для создания порта</p></figcaption></figure>

Порт создан, переходим к настройке

### 3. Настройка GeyserMC

Заходим в конфиг GeyserMC, по пути `plugins/geyser-Ваш тип/config.yml`.&#x20;

Выполняем 3 настройки:

1. Раздел `Bedrock`, поле Port меняем на скопированный ранее дополнительный порт

<figure><img src="../../.gitbook/assets/image (3).png" alt=""><figcaption><p>Изменение порта на свой</p></figcaption></figure>

2. Раздел `Remote`:

* `auth-type: floodgate`
* `allow-password-authentication: false`

<figure><img src="../../.gitbook/assets/image (4).png" alt=""><figcaption><p>Изменение типа авторизации.</p></figcaption></figure>

Это фундаментальные настройки. Вы также можете настроить показ Motd вверху или максимум игроков с bedrock чуть ниже. Нажимаем сохранить содержимое, и заходим в файл `plugins/floodgate/config.yml`. Там изменяем `username-prefix: ""`. Это необязательно, однако поможет не отличать bedrock игроков. Этот параметр добавляет указанный префикс к никнейму игроков с bedrock

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption><p>Floodgate конфигурация</p></figcaption></figure>

&#x20;Сохраняем файл, и перезапускаем сервер. Теперь вы можете зайти на сервер по под. домену и дополнительному порту. Например e1.veroid.net и порт 25886.

{% hint style="success" %}
Гейзер настроен успешно. Приятной игры.
{% endhint %}
