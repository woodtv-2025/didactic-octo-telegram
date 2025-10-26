# Тестирование REST API SkyEng Teachers

## О проекте
Комплексная коллекция Postman для тестирования API управления расписанием. 
Демонстрирует полный цикл работы с событиями: создание, изменение, копирование, удаление.

## Что демонстрирует
- ✅ Полное тестирование CRUD-операций
- 🎯 Автоматизация на JavaScript (Pre-request и Test scripts)
- 📊 Визуализация результатов
- 🔄 Управление тестовыми данными
- 📝 Детальное документирование

## Структура
- `ApiSkyEng21_10.postman_collection.json` - основная коллекция
- ## Структура коллекции
- **✅ Полный цикл:** Последовательные сценарии создания, изменения, копирования и удаления событий.
- **🛠️ Утилиты удаления:** Инструменты для массового управления тестовыми данными.
- `ApiSkyEng21_10.postman_test_run_Negative` - тест-ран негативных запросов
- `ApiSkyEng21_10.postman_test_run_Positiv` - тест-ран полного цикла CRUD
- `ApiSkyEng21_10.postman_test_run_UtilDel` - тест-ран запросов очистки рабочего пространства

## Как запустить
1. Импортируйте коллекцию в Postman
2. Установите переменные `baseUrl` и `token_global`
3. Запустите запросы из папки "✅ Полный цикл"
![Visual2](https://github.com/user-attachments/assets/c8d7d29e-57fd-4dcc-a5d2-728e6733ff1c)
![Visual1](https://github.com/user-attachments/assets/cc4bac5a-6e4d-4220-a4c8-98edd7d34a4f)
![Skyeng_collection](https://github.com/user-attachments/assets/1fdd2f4b-3d82-465e-bf14-74b8d3dc222b)
![Console](https://github.com/user-attachments/assets/7f7be836-0b51-4a08-a015-e60f8c9d5e29)
