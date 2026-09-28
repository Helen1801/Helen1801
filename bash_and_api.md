# Практика работы с Bash и API

В этом файле собраны команды, которые я использовала для отработки навыков работы с командной строкой и API Petstore.

## Выполненные команды
```
touch bash2.txt
cd ~
mkdir "test 3"
cd "test 3"
printf "row1\nrow2\nrow3\nrow4\n" > 4
printf "row1\nrow2\nrow3\nrow4\n" > 5
printf "row1\nrow2\nrow3\nrow4\n" > 6
grep "row2" 5
grep -r "row" .
grep -c "row" 6
find . -name "5"
find . -name "5" -delete
echo "test" >> 4
sed -i 's/test/fail/' 4
echo "test" >> 4
ps aux
kill 2096
ping rusau.net
ping -n 5 rusau.net
curl -X GET "https://petstore.swagger.io/v2/pet/findByStatus?status=available" -H "User-Agent: curl"
curl -X POST "https://petstore.swagger.io/v2/user" -H "Content-Type: application/json" -H "User-Agent: curl" -d '{"id": 123, "username": "testuser", "firstName": "Test", "lastName": "User", "email": "test@example.com", "password": "password123", "phone": "1234567890", "userStatus": 1}'
```
