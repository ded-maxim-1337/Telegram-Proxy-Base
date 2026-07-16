# MTProto прокси для Telegram

Автоматически обновляемый список проверенных **MTProto**-прокси для Telegram.
Сбор из открытых источников, проверка доступности, probe resistance (Fake-TLS) и публикация.

Обновлено: **2026-07-16 23:58 UTC** · **1** рабочих прокси

---

## Актуальные списки

Списки обновляются автоматически при каждом прогоне пайплайна.

| Тип | Список | Примечание |
| --- | --- | --- |
| MTProto (все) | [proxy_all.txt](https://raw.githubusercontent.com/ded-maxim-1337/Telegram-Proxy-Base/gh-pages/proxy_all.txt) | Ссылки `tg://proxy?...` для парсеров и ботов |
| MTProto (с заголовком) | [proxies.txt](https://raw.githubusercontent.com/ded-maxim-1337/Telegram-Proxy-Base/gh-pages/proxies.txt) | То же, с комментарием и датой |
| JSON (метаданные) | [proxy_all_verified.json](https://raw.githubusercontent.com/ded-maxim-1337/Telegram-Proxy-Base/gh-pages/proxy_all_verified.json) | ping, domain, probe_resistant |

**Сайт:** [http://31.128.40.126:8000](http://31.128.40.126:8000) — полный список, проверка и подключение.

---

## Мои проекты

| Проект | Описание | Ссылка |
| --- | --- | --- |
| Telegram-канал | Обновления списков и новости | [Канал](https://t.me/tg_proksi) |
| Сайт проекта | Документация и полный список | [Сайт](http://31.128.40.126:8000) |
| [Бот проекта](https://t.me/tgproxyz_bot) | Автоматическая выдача прокси и ключей | [Bot](https://t.me/tgproxyz_bot) |
| GitHub | Списки прокси (этот репозиторий) | [GitHub](https://github.com/ded-maxim-1337/Telegram-Proxy-Base) |

---

## VPN-сервис

Прокси работают **только для Telegram**. Для полноценного доступа в интернет:

| Сервис | Ссылка |
| --- | --- |
| VPN Telegram-бот | [https://t.me/awxvpn_bot](https://t.me/awxvpn_bot) |
| Сайт VPN | [https://awxweb.site](https://awxweb.site) |

---

## Как это работает

1. **Сбор** — прокси из Telegram-каналов и топиков.
2. **Проверка** — TCP ping, Telethon-подключение, probe resistance (Fake-TLS).
3. **Публикация** — этот репозиторий, Telegram-канал и сайт.

Сортировка: сначала probe-resistant, затем по возрастанию пинга.

---

## Дисклеймер

Прокси предоставляются «как есть». Качество зависит от внешних источников.
Репозиторий не гарантирует анонимность или защиту от компрометации.
