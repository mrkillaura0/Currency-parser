# 💱 Парсер курсов валют (Беларусь)

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

Скрипт на Python для автоматического сбора актуальных курсов **доллара, евро и российского рубля** с [myfin.by](https://myfin.by). Данные сохраняются в Excel-файл с временными метками.

---

## 🛠 Возможности

- 📊 Сбор курсов **USD, EUR, RUB** в реальном времени
- 💾 Сохранение в **Excel (.xlsx)** с датой и временем
- 🔄 Резервный источник данных — **API Нацбанка РБ** при недоступности myfin.by
- ⏱ Готов к **ежедневному/автоматическому** запуску (cron, Task Scheduler)

---

## 📦 Установка и запуск

```bash
# 1. Клонировать репозиторий
git clone https://github.com/mrkillaura0/Currency-parser.git
cd Currency-parser

# 2. Установить зависимости
pip install -r requirements.txt

# 3. Запустить
python currency_parser.py
```

После запуска в папке появится файл `currency_rates.xlsx` с актуальными курсами.

---

## 🔧 Технологии

| Библиотека | Назначение |
|---|---|
| `requests` | HTTP-запросы |
| `BeautifulSoup4` | Парсинг HTML |
| `pandas` | Обработка данных |
| `openpyxl` | Запись в Excel |

---

## 👤 Автор

Python-разработчик, специализируюсь на автоматизации и работе с данными.

**Принимаю заказы:**

- 🕷 Парсинг сайтов и сбор данных
- 🤖 Telegram-боты
- ⚙️ Скрипты автоматизации
- 📊 Обработка Excel / CSV

**Связаться:**

- Telegram: [@Vin_ches_ter](https://t.me/Vin_ches_ter)
- Email: [mrkillaura0@gmail.com](mailto:mrkillaura0@gmail.com)
