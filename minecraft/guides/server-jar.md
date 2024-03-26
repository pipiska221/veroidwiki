# Invalid jarfile

<figure><img src="https://github.com/Kanorto/VWIKI/assets/77388225/9445ecfb-8e2d-4343-891b-a7c2acb5d8ac" alt=""><figcaption><p>Скриншот ошибки</p></figcaption></figure>

Стандартная ошибка при которой Java не может найти или использовать jar файл. Ниже приведу несколько причин, как решить эту проблему.

## 1. Не изменили параметр запуска

Стандартная ошибка заключается в том, что вы не переименовали server.jar в настройках. Рассказываю как это сделать.

<figure><img src="https://github.com/Kanorto/VWIKI/assets/77388225/3ece6cbf-f565-40f0-9776-885774f89836" alt=""><figcaption><p>Быстрый гайд на картинке</p></figcaption></figure>

1. Заходим в <mark style="color:blue;">`Файлы`</mark> или заранее копируем имя файла.
2. Копируем имя файла, например <mark style="color:purple;">`purpur-1.20.2-2095.jar`</mark>.
3. Заходим в раздел <mark style="color:blue;">`Параметры запуска`</mark>.
4. Ищем поле <mark style="color:blue;">`Имя ядра у сервера`</mark>.&#x20;
5. Вводим ранее скопированное имя файла, **ОБЯЗАТЕЛЬНО с **<mark style="color:purple;">**.JAR**</mark>
6. (Необязательно) Выбираем версию java в соответствии с подсказкой:&#x20;

{% hint style="info" %}
1.19 - 1.20.4 - Java 17 \
1.17 - 1.18.2 - Java 16 \
Under 1.16.5 - Java 8
{% endhint %}

**Если это не помогло, переустановите ядро сервера, возможно оно повредилось при передаче.**
