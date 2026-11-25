# Pensieve — сайт

- `index.html` — дизайн і логіка сторінки.
- `content/site.json` — увесь змінний вміст: товари й ціни, фото, галерея, відгуки, догляд, контакти.
  Його редагує адмінка (`/admin`), тож у коді товари вручну не вписуються.
- `photos/` — фото (сюди ж адмінка завантажує нові).
- `admin/` — адмінка Decap CMS. У `admin/config.yml` вказано, на якому GitHub-репозиторії лежить сайт.
- Сайт відкритий для всіх: https://pensieve.com.ua
- `robots.txt`, `sitemap.xml` — для Google; `photos/og.jpg` — картинка в превʼю посилання (Telegram, Instagram, Viber).
  Якщо зміниться адреса сайту — замініть її в `sitemap.xml`, `robots.txt` і в `<head>` файлу `index.html`.

Якщо змінюєте сайт через Claude: тексти й товари — у `content/site.json`, дизайн — в `index.html`.
