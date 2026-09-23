# gruz-ekb.ru (GitHub Pages)

Статическая страница для GitHub Pages.

## Локальный просмотр

Откройте `index.html` двойным кликом, либо:

```powershell
start .\index.html
```

macOS: `open index.html`, Linux: `xdg-open index.html`.

## Деплой на GitHub Pages

1. Создайте репозиторий на GitHub и запушьте сюда файлы.
2. В репозитории откройте **Settings → Pages**.
3. Включите публикацию из ветки `main` и папки `/ (root)`.

## Домен

Файл `CNAME` содержит домен `gruz-ekb.ru`.
После включения Pages настройте DNS у регистратора:

- `A` для `@`:
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`
- `CNAME` для `www` → `petushokmaxorka-ai.github.io`

Далее в **Settings → Pages** укажите Custom domain `gruz-ekb.ru` и включите HTTPS.

Домен должен быть зарегистрирован и делегирован: пока в репозитории лежит
`CNAME`, GitHub перенаправляет `petushokmaxorka-ai.github.io/gruz-ekb-pages/`
на `gruz-ekb.ru`, и если домен не резолвится, сайт недоступен. Чтобы
временно публиковать сайт по адресу
`https://petushokmaxorka-ai.github.io/gruz-ekb-pages/`, удалите `CNAME`
(или очистите Custom domain в **Settings → Pages**).

