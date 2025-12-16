# Sabor — Прокат и аренда автомобилей в Перми

Статичный сайт компании SABOR для аренды автомобилей в Перми, переведённый с WordPress на нативный HTML/CSS/JS.

## Описание

Полностью рабочий сайт без использования библиотек и фреймворков:
- Чистый HTML5, CSS3, Vanilla JavaScript
- Адаптивная вёрстка для мобильных устройств и десктопа
- Все страницы: главная с тарифами, прокат, условия аренды, контакты
- Готов к размещению на любом статическом хостинге (GitHub Pages, Netlify, Vercel и т.п.)

## Структура проекта

    saborauto-static/
    ├── index.html                                    # Главная: тарифы и автомобили
    ├── arenda-i-prokat-avtomobilej-v-permi.html      # Прокат
    ├── usloviya-arendy.html                          # Условия аренды
    ├── kontakty.html                                 # Контакты
    ├── css/
    │   └── style.css                                 # Общие стили и адаптив
    ├── js/
    │   └── main.js                                   # Мобильное меню
    └── img/
        ├── kia-rio-4.jpg
        ├── hyundai-solaris.jpg
        ├── skoda-rapid.jpg
        ├── moskvich-3.jpg
        ├── vw-polo.jpg
        ├── changan-lamora.jpg
        ├── changan-eado-plus.jpg
        └── ...                                       # Остальные изображения

## Запуск локально

1. Склонируйте репозиторий:
git clone https://github.com/ваш-username/saborauto-static.git
cd saborauto-static

text

2. Откройте `index.html` в браузере или используйте локальный веб-сервер:
Python 3
python -m http.server 8000

Node.js (если установлен http-server)
npx http-server

text

3. Перейдите в браузере на `http://localhost:8000`

## Деплой

### GitHub Pages
1. Загрузите проект в GitHub
2. Settings → Pages → Source: main branch → Save
3. Сайт будет доступен по адресу `https://AlexanderKuzikov.github.io/saborauto-static/`

### Netlify / Vercel
Просто перетащите папку проекта в веб-интерфейс или подключите GitHub-репозиторий.

## Особенности

- ✅ Без WordPress, jQuery, фреймворков
- ✅ Нативный CSS Grid и Flexbox для сетки
- ✅ Минимальный JS для мобильного меню
- ✅ SEO-friendly структура (meta-теги, семантичная разметка)
- ✅ Полностью статичный, быстрая загрузка

## Доработка и улучшения

Планируемые улучшения:
- [ ] Добавить реальные изображения автомобилей из оригинального сайта
- [ ] Встроить карту Яндекс/Google на страницу контактов
- [ ] Оптимизировать изображения (WebP, ленивая загрузка)
- [ ] Добавить микроразметку Schema.org для карточек автомобилей
- [ ] Настроить Lighthouse score 95+

## Контакты компании SABOR

- Телефоны: +7-912-882-15-36, (342) 2-770-770
- Адрес: Пермь, ул. Петропавловская, 15 А, офис 34
- WhatsApp: [wa.me/79128821536](https://wa.me/79128821536)

## Лицензия

Apache License 2.0 — свободное использование, модификация и распространение с указанием авторства и сохранением уведомления о лицензии.

См. [LICENSE](LICENSE) для подробностей.
