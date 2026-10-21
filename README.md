# СИГНУМ — сайт агентства системного продвижения

Одностраничный сайт: `index.html` (вся вёрстка, стили и скрипты внутри).
Шрифты, GSAP и Three.js подгружаются с CDN, сборка не нужна.

## Как опубликовать на GitHub Pages

1. Создайте на GitHub новый публичный репозиторий, например `signum`.
2. Нажмите **Add file → Upload files** и перетащите файлы `index.html`, `README.md` и `.nojekyll`.
   Нажмите **Commit changes**.
3. Откройте **Settings → Pages**. В блоке *Build and deployment* выберите
   *Source: Deploy from a branch*, ветку `main` и папку `/ (root)`, нажмите **Save**.
4. Через 1–2 минуты сайт будет доступен по адресу
   `https://<ваш-логин>.github.io/signum/`.

Свой домен можно подключить там же, в **Settings → Pages → Custom domain**.

## Заявки на почту

Форма отправляет заявки через бесплатный сервис [FormSubmit](https://formsubmit.co)
на адрес, указанный в `index.html` в строке:

```js
const LEAD_EMAIL = 'vikulovmih27@gmail.com';
```

После публикации отправьте первую тестовую заявку с сайта — FormSubmit пришлёт
на эту почту письмо с кнопкой **Activate**. После подтверждения все заявки
начнут приходить письмами в виде таблицы.
