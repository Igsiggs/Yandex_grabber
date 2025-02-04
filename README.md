<!-- Logo -->
<p align="center">
    <a href="#">
      <img height="128" wight="128" src="https://user-images.githubusercontent.com/60988563/132104021-48ec1d2b-e98b-46c5-8d3b-0baab5fbe3af.png">
    </a>
  </p>

<!-- Title -->
<h1 align="center">🔍 YMapsGrabber 🗺</h1>

<!-- Classic badges -->
<p align="center">
    <a href="https://www.codefactor.io/repository/github/chernyshov-dev/ymapsgrabber">
        <img src="https://www.codefactor.io/repository/github/chernyshov-dev/ymapsgrabber/badge" alt="CodeFactor"/>
    </a>
    <a href="#">
        <img src="https://img.shields.io/github/license/chernyshov-dev/ymapsgrabber"/>
    </a>
    <a href="https://app.fossa.com/projects/git%2Bgithub.com%2Fchernyshov-dev%2FYMapsGrabber?ref=badge_shield" alt="FOSSA Status">
        <img src="https://app.fossa.com/api/projects/git%2Bgithub.com%2Fchernyshov-dev%2FYMapsGrabber.svg?type=shield"/>
    </a>
    <a href="#">
        <img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/chernyshov-dev/ymapsgrabber"/>
    </a>
</p>

---

> Граббер для Яндекс.Карт, собирающий информацию об организациях в выбранной области поиска

---

## Стек
- Python 3.9
- Selenium + safaridriver
- beautifulsoup4 + lxml
- json

## Список собираемой информации с Яндекс.Карт
- Название организации
- Адрес
- Сайт организации
- Часы работы (по дням недели)
- Ссылка на карточку организации
- Меню/услуги
- Рейтинг
- Отзывы

## Пример OUTPUT.json
<p>Результат запроса "Москва ресторан" находится <a href="https://github.com/chernyshov-dev/YMapsGrabber/blob/main/example.json">здесь</a></p>

## Установка и запуск
```console
git clone https://github.com/chernyshov-dev/YMapsGrabber.git
cd YMapsGrabber/grab-grab
pip3 install -r requirements.txt
python3 main.py
```

## Лицензия
[GNU General Public License v3.0](https://github.com/chernyshov-dev/YMapsGrabber/blob/main/LICENSE)
#   Y a n d e x _ g r a b b e r  
 