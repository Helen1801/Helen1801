# Практика работы с Bash (Командная строка)

В этом файле собраны команды, которые я использовала для отработки навыков работы с командной строкой в рамках курса.

**Что было сделано:**
* Создание файлов и папок (`touch`, `mkdir`).
* Переход по директориям (`cd`).
* Работа с текстом: запись в файлы (`printf`), поиск (`grep`), замена (`sed`).
* Поиск файлов в системе (`find`).
* Работа с процессами (`ps aux`, `kill`).
* Проверка сети (`ping`).
* Выполнение GET и POST запросов к API через `curl` (на примере Petstore).

## Примеры выполненных команд:

```bash
# Создание файла и папки
touch bash2.txt
mkdir "test 3"

# Поиск строки в файле
grep "row2" 5

# Замена текста
sed -i 's/test/fail/' 4

# GET-запрос к API Petstore
curl -X GET "https://petstore.swagger.io/v2/pet/findByStatus?status=available" -H "User-Agent: curl"

# POST-запрос для создания пользователя
curl -X POST "https://petstore.swagger.io/v2/user" -H "Content-Type: application/json" -H "User-Agent: curl" -d '{"id": 123, "username": "testuser", "firstName": "Test"}'
