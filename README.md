# gruz-ekb.ru (GitHub Pages)

Статическая страница для GitHub Pages.

## Локальный просмотр

Откройте `index.html` двойным кликом, либо:

```powershell
start .\index.html
```

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
- `CNAME` для `www` → `<ваш-логин>.github.io`

Далее в **Settings → Pages** укажите Custom domain `gruz-ekb.ru` и включите HTTPS.

