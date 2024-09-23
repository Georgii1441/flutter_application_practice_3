# Страница с карточками футболистов

ЭФБ0-02-22 Епишин Г.А.

Простое приложение на Flutter, которое отображает карточки с футболистами. Каждая карточка футболиста представлена отдельным компонентом и содержит информацию и фото игрока.

## Особенности

- Карточки игроков — это переиспользуемые компоненты.

## Структура проекта

```bash
lib/
│
├── main.dart # Точка входа в приложение.
├── components/
│   └── item_player_card.dart # Компонент-виджет для отображения карточки игрока.
├── models/
│   └── player_card.dart # Класс модели, представляющий футболиста.
└── pages/
    └── home_page.dart # Компонент-виджет (Домашняя страница)
```

## Скриншоты

### Веб версия:

![Screenshot Web Version](https://github.com/Georgii1441/flutter_application_practice_3/raw/main/screenshots/web_version.jpg)

### Мобильная версия:

![Screenshot Mobile Version](https://github.com/Georgii1441/flutter_application_practice_3/raw/main/screenshots/mobile_version.jpg)
