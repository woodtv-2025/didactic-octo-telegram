# 📅 SkyEng Teachers API Testing

![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![API Testing](https://img.shields.io/badge/API-Тестирование-blue?style=for-the-badge)
![REST](https://img.shields.io/badge/REST-API-green?style=for-the-badge)

Комплексная коллекция Postman для тестирования API управления расписанием SkyEng. Демонстрирует полный цикл работы с событиями: создание, изменение, копирование и удаление.

## 📋 О проекте

Автоматизированная коллекция тестов для REST API SkyEng Teachers. Обеспечивает полное покрытие CRUD-операций с событиями расписания. Включает позитивные и негативные сценарии, визуализацию результатов и утилиты для управления тестовыми данными.

## 🚀 Возможности

- **Полный CRUD-цикл**: создание, изменение, копирование и удаление событий
- **Автоматизация на JavaScript**: Pre-request и Test-скрипты
- **Визуализация результатов**: HTML-отчёты для анализа
- **Управление тестовыми данными**: утилиты для массового удаления
- **Детальное документирование**: структурированная коллекция

## 🏗 Структура коллекции

### Основные папки:
- **✅ Полный цикл** - последовательные сценарии создания, изменения, копирования и удаления событий
- **🛠️ Утилиты удаления** - инструменты для массового управления тестовыми данными

### Тест-раны:
- `ApiSkyEng21_10.postman_test_run_Positiv` - тест-ран полного цикла CRUD
- `ApiSkyEng21_10.postman_test_run_Negative` - тест-ран негативных запросов
- `ApiSkyEng21_10.postman_test_run_UtilDel` - тест-ран запросов очистки рабочего пространства

## 🛠 Технологии

- **Postman** - тестовый раннер и управление коллекциями
- **JavaScript** - Pre-request и Test-скрипты
- **REST API** - методология тестирования
- **HTML** - визуализация результатов

## 📦 Установка и запуск

### 1. Клонирование репозитория

```bash
git clone https://github.com/woodtv-2025/skyeng-rest-api.git
```

### 2. Настройка в Postman
1. Импортируйте файл коллекции `ApiSkyEng21_10.postman_collection.json`
2. Настройте переменные окружения:
    - baseUrl: URL вашего окружения SkyEng
    - token_global: токен авторизации

### 3. Запуск тестов
  - Откройте Postman Runner
  - Выберите коллекцию "ApiSkyEng21_10"
  - Запустите выполнение

### 📊 Визуализация
#### Результаты тестирования

![Visual2](https://github.com/user-attachments/assets/c8d7d29e-57fd-4dcc-a5d2-728e6733ff1c)
![Visual1](https://github.com/user-attachments/assets/cc4bac5a-6e4d-4220-a4c8-98edd7d34a4f)

#### Скриншоты 
![Skyeng_collection](https://github.com/user-attachments/assets/1fdd2f4b-3d82-465e-bf14-74b8d3dc222b)
![Console](https://github.com/user-attachments/assets/7f7be836-0b51-4a08-a015-e60f8c9d5e29)

### 🤝 Участие в разработке
- Сделайте форк проекта
- Создайте ветку для функции (git checkout -b feature/amazing-feature)
- Закоммитьте изменения (git commit -m 'Add some amazing feature')
- Запушьте в ветку (git push origin feature/amazing-feature)
- Откройте Pull Request

### 📄 Лицензия
Этот проект лицензирован под MIT License - подробности в файле LICENSE.

## 👥 Авторы

- GitHub: woodtv-qa
- Email: woodtv2013@yandex.ru

<div align="center">

### 🚀 Удачного тестирования!

</div>
```
