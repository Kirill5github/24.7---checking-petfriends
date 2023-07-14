# 24.7-Отчетное задание
Репозиторий содержит следующие файлы:
Директория /tests
- settings.py - содержит все необходимые данные для входа - ссылается на файл .env
- api.py - библиотека к REST api сервису веб-сайта Pet Friends
- test_pet_friends.py - содержит тесты для веб-сайта Pet Friends
Директория /tests/images
-картинки для теста добавления питомца и теста добавления картинки
dog1.jpg, dog2.jpg, dog1.txt

Выполненная работа:
Всего было добавлено два метода в файл api.py: метод add_new_pet_no_photo - добавление питомца без фото и метод
add_photo_to_pet - добавление фото к существующему питомцу.

Написано 10 тест-кейсов:
- 2 позитивных - test_add_new_pet_no_photo (строка 90) - выполнен успешно; test_successful_add_photo_to_pet (строка 105) - выполнен успешно
- 8 негативных - test_unsuccessful_get_api_key_for_no_user (строка 128) - выполнен успешно; test_unsuccessful_add_new_pet_with_no_name (строка 128) - провален; test_unsuccessful_add_new_pet_with_no_type (строка 152) - провален; test_unsuccessful_add_new_pet_with_no_age (строка 165) - провален; test_unsuccessful_add_new_pet_with_no_photo (строка 179) - выполнен успешно; test_unsuccessful_add_new_pet_with_negative_age (строка 193) - провален; test_unsuccessful_add_new_pet_with_text_file (строка 207) - провален; test_unsuccessful_add_new_pet_with_long_name (строка 221) - провален.
