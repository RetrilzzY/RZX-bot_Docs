---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 🌟 Основные команды

***

{% hint style="info" %}
**Подсказка**

**`<...>`** - обязательный аргумент\
**`[...]`** - необязательный аргумент

\
**`/команда`**- вызов через слэш(/)\
**`!команда`** - вызов через префикс (по умолчанию `!`, можно изменить при помощи _`/manage-prefix`_ или через [панель управления](https://dash.rzx-bot.top))\
**`команда`** - вызов через слэш и префикс
{% endhint %}

<details>

<summary><code>/manage-prefix</code> - Установите свой префикс для вашего сервера</summary>

**Пример:**\
`/manage-prefix prefix: ?`

</details>

<details>

<summary><code>/economy-settings</code> - Управление модулем экономики</summary>

**Пример:**\
`/economy-settings settings: перевод и принятие средств с других серверов action: разрешить`

</details>

{% hint style="warning" %}
Для использования команд`/manage-prefix /economy-settings` необходима роль с разрешением **"Управление сервером"** или вы должны быть **администратором**
{% endhint %}

***

<details>

<summary><code>/image-search</code> - Поиск изображения по текстовому запросу</summary>

**Пример:**\
`/image-search query: apple`

</details>

<details>

<summary><code>img-kandinsky img-sdxl</code> - ИИ генерации изображений</summary>

**Использование:**\
`img-kandinsky <промпт> | img-sdxl <промпт>`

**Пример:**\
`!img-kandinsky breathtaking night street of Tokyo, cars, neon lights. award-winning, professional, highly detailed`

<img src="../.gitbook/assets/kandinsky_output.png" alt="" data-size="original">

</details>

<details>

<summary><code>/magic-ball, /nekos-ball</code> - Один верный ответ на твой вопрос (но это не точно)</summary>

**Пример:**\
`/magic-ball question: Это вопрос?`

</details>

<details>

<summary><code>/message-maker-lite</code> - Полезный инструмент для создания продвинутых cообщений (упрошенная версия)</summary>

**Пример:**\
`/message-maker-lite title: Это эмбед description: Да, это так color: blue text: @RZX-bot#2626`

<img src="../.gitbook/assets/message-maker-lite.png" alt="" data-size="original">

</details>

<details>

<summary><code>/message-maker-pro</code> - Полезный инструмент для создания продвинутых сообщений (продвинутая версия)</summary>

Все визуально и просто

<img src="../.gitbook/assets/message-maker-pro.png" alt="" data-size="original">

</details>

***

<details>

<summary><code>purge</code> - Очистка n количества сообщений в текущем канале</summary>

**Использование:**\
**`purge <количество сообщений>`**

**Пример:**\
**`!purge 5`**

</details>

<details>

<summary><code>purge_until</code> - Очистить сообщения в канале до заданного message_id</summary>

**Использование:**\
`purge_until <id сообщения>`

**Пример:**\
`!purge_until 1200619381080731648`

</details>

<details>

<summary><code>purge_user</code> - Очистить все сообщения &#x3C;Пользователя> в каждом канале за последние [n=5] минут</summary>

**Использование:**\
`purge_user <упоминание участника> [За последние сколько минут (по умолчанию 5)]`

**Пример:**\
`!purge_user @retrilzzy 10`

</details>

{% hint style="warning" %}
Для использования команд `purge, purge_until, purge_user` необходима роль с разрешением **"Выгонять участников"** или вы должны быть **администратором**
{% endhint %}

***

<details>

<summary><code>user-info</code> - Узнать информацию о себе или участнике</summary>

**Использование:**\
`user-info [упоминание участника]`

**Пример:**\
`!user-info @retrilzzy`

</details>

<details>

<summary><code>server-info</code> - Узнать информацию о сервере</summary>

**Пример:**\
`!server-info`

</details>

<details>

<summary><code>/waifu-pics, /nekos-life, /waifu-im</code> - Изображения/гифки в аниме стиле</summary>

**Примеры:**\
`/waifu-im tag: waifu tag2: uniform`\
`/nekos-life tag: neko`

</details>
